# Instalação e Uso do Zphisher no Kali Linux

O Zphisher é uma ferramenta de phishing automatizada que simplifica a criação de páginas de login falsas. **Lembre-se:** o uso de ferramentas de phishing para atividades ilegais é estritamente proibido e pode resultar em consequências legais severas. Use o Zphisher apenas para fins educacionais e em ambientes controlados, como testes de penetração em seus próprios sistemas.

## 1. Instalação das Dependências

* Abra um terminal no Kali Linux.
* Atualize os pacotes do sistema:
    ```bash
    sudo apt update && sudo apt upgrade -y
    ```
* Instale as dependências necessárias:
    ```bash
    sudo apt install git python3 python3-pip php curl -y
    sudo pip3 install requests
    ```

## 2. Clonagem do Repositório Zphisher

* Use o Git para clonar o repositório Zphisher do GitHub:
    ```bash
    git clone [https://github.com/htr-tech/zphisher.git](https://github.com/htr-tech/zphisher.git)
    ```
* Navegue até o diretório Zphisher:
    ```bash
    cd zphisher
    ```

## 3. Execução do Zphisher

* Dê permissão de execução ao script:
    ```bash
    chmod +x zphisher.sh
    ```
* Execute o script:
    ```bash
    ./zphisher.sh
    ```

## 4. Utilização do Zphisher

* Após a execução do script, o Zphisher exibirá um menu com várias opções de sites para clonar. Selecione o site que deseja clonar (por exemplo, Facebook, Instagram, Google).
* O Zphisher também oferece diversas opções de envio de links, como ngrok, localtunnel, cloudflared, ou hospedagem em servidor local. Selecione a opção desejada.
* O Zphisher gerará um link de phishing. Envie esse link para a vítima.
* Quando a vítima inserir suas credenciais na página falsa, elas serão exibidas no seu terminal.

## Considerações Importantes

* **Ética e Legalidade:** Use o Zphisher apenas para fins educacionais e em ambientes controlados. O phishing é uma atividade ilegal e pode causar danos significativos às vítimas.
* **ngrok e outras opções:** ngrok e cloudflared são serviços que criam túneis seguros para expor um servidor local à Internet. Eles são úteis para testar páginas de phishing em dispositivos externos.
* **Antivírus:** Alguns antivírus podem detectar o Zphisher como uma ferramenta maliciosa. Desative temporariamente o antivírus se encontrar problemas, mas lembre-se de reativá-lo após o uso.
* **Atualizações:** O Zphisher é atualizado com frequência. Para obter a versão mais recente, use o comando `git pull` dentro do diretório Zphisher.
* **Responsabilidade:** O uso do Zphisher é de sua total responsabilidade. Este guia é fornecido apenas para fins educacionais.

## Alternativas ao Zphisher

* **SocialFish:** Outra ferramenta de phishing automatizada com recursos semelhantes ao Zphisher.
* **Evilginx2:** Uma estrutura de phishing mais avançada que permite capturar cookies de sessão, contornando a autenticação de dois fatores.
* **GoPhish:** Uma estrutura de phishing de código aberto projetada para testes de conscientização de segurança.

Lembre-se de que a melhor defesa contra o phishing é a conscientização. Eduque-se e seus usuários sobre os riscos do phishing e como identificar e evitar ataques.


## Uso

1.  **Execute o script:** No terminal, dentro do diretório, use `bash zphisher.sh`.
2.  **Selecione o tipo de ataque:** Escolha entre as opções disponíveis (redes sociais, jogos, etc.).
3.  **Selecione o modelo:** Escolha o modelo de página de login desejado.
4.  **Configure o túnel:** Selecione uma opção de túnel (Ngrok, Cloudflare Tunnel, etc.).
5.  **Envie o link:** O Zphisher gerará um link para a página de phishing. Envie-o para a vítima.

### Exemplo: Phishing no Instagram

1.  Execute o Zphisher e selecione a opção do Instagram.
2.  Escolha um modelo de página de login do Instagram.
3.  Configure o túnel com Ngrok.
4.  O Zphisher gerará um link Ngrok.
5.  Envie o link para a vítima, incentivando o login.
6.  As credenciais inseridas serão capturadas.

## Medidas de Proteção

* **Verifique a URL:** Certifique-se de que a URL da página de login é legítima.
* **Desconfie de links:** Evite clicar em links de fontes desconhecidas.
* **Use 2FA:** Ative a autenticação de dois fatores em suas contas.
* **Mantenha o software atualizado:** Atualize seu sistema operacional e aplicativos.
* **Eduque-se sobre phishing:** Aprenda a identificar e evitar ataques.

## Observações

* O Zphisher pode não funcionar em todas as plataformas e pode ser detectado.
* O uso para atividades ilegais é crime.
* Use apenas para fins educacionais e com autorização.
