# Ataque de Phishing Usando o SEToolkit no Kali Linux

O Social-Engineer Toolkit (SET) no Kali Linux é uma ferramenta poderosa para testes de penetração e simulações de ataques de engenharia social, incluindo phishing. No entanto, é crucial lembrar que o uso do SET para atividades ilegais é estritamente proibido e pode ter consequências graves.

## Cenário de Ataque de Phishing com SET

Imagine que um invasor deseja obter as credenciais de login de funcionários de uma empresa. Ele pode usar o SET para criar uma página de login falsa que imita a página de login da intranet da empresa. Em seguida, ele pode enviar um e-mail de phishing para os funcionários, solicitando que eles façam login na página falsa para verificar suas informações.

## Passos para Realizar um Ataque de Phishing Simulado com SET

1.  **Abra o SET:** No terminal do Kali Linux, digite `setoolkit` e pressione Enter.
2.  **Selecione a opção "Social-Engineering Attacks":** Digite `1` e pressione Enter.
3.  **Selecione a opção "Website Attack Vectors":** Digite `2` e pressione Enter.
4.  **Selecione a opção "Credential Harvester Attack Method":** Digite `3` e pressione Enter.
5.  **Selecione a opção "Site Cloner":** Digite `2` e pressione Enter.
6.  **Insira o endereço IP do seu Kali Linux:** O SET exibirá o endereço IP da sua máquina. Digite-o e pressione Enter.
7.  **Insira a URL da página de login que você deseja clonar:** Por exemplo, `https://intranet.empresa.com`. Pressione Enter.
8.  **O SET criará uma página de login falsa:** A página será hospedada em um servidor web local no seu Kali Linux.
9.  **Envie o e-mail de phishing:** Crie um e-mail convincente que incentive os funcionários a clicar no link para a página falsa. O link deve usar o endereço IP do seu Kali Linux.

## Detalhes Adicionais

* O SET oferece outras opções de ataque de phishing, como a criação de páginas de login falsas com modelos pré-definidos.
* O invasor pode usar técnicas de engenharia social para tornar o e-mail de phishing mais convincente, como usar um remetente falso ou criar um senso de urgência.
* É possível utilizar engenharia reversa para clonar sites complexos, e editar o código para que se ajuste as suas necessidades.
* Ferramentas como o Ngrok, permitem que você exponha o servidor web local do Kali Linux para a internet, permitindo que o ataque de phishing seja realizado em vítimas fora da sua rede local.

## Exemplo de Aplicação Real

Empresas de segurança cibernética usam o SET para realizar testes de penetração em seus clientes. Eles simulam ataques de phishing para identificar vulnerabilidades e conscientizar os funcionários sobre os riscos.

## Medidas de Proteção

* Verifique sempre o endereço URL de páginas de login antes de inserir suas credenciais.
* Desconfie de e-mails que solicitam informações pessoais ou financeiras.
* Mantenha seu software antivírus e firewall atualizados.
* Eduque-se sobre as táticas de phishing e como se proteger.

**Lembre-se:** O uso do SET para atividades ilegais é crime. Use-o apenas para fins educacionais e de teste de penetração, com a devida autorização.
