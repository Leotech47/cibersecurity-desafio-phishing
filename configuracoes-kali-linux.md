# Configurar o teclado no Kali Linux para o padrão ABNT2 é um processo simples, mas crucial para uma experiência de digitação confortável em português. 
- Existem duas maneiras principais de realizar essa configuração:

**1. Através das Configurações Gráficas:**

* **Acesse as Configurações:**
    * Vá para o menu "Settings" (Configurações) do Kali Linux.
    * Procure por "Region & Language" (Região e Idioma).
* **Adicione o Layout ABNT2:**
    * Na seção "Input Sources" (Fontes de Entrada), clique no botão "+".
    * Procure por "Português (Brasil)" e selecione o layout "Português (Brasil, abnt2)".
    * Adicione o layout à lista.
* **Defina como Padrão:**
    * Certifique-se de que o layout ABNT2 esteja no topo da lista de fontes de entrada para defini-lo como padrão.

**2. Através do Terminal:**

* **Utilize o comando `setxkbmap`:**
    * Abra um terminal.
    * Digite o seguinte comando e pressione Enter:
        * `setxkbmap br abnt2`
    * Esse comando define o layout do teclado para ABNT2.
* **Para tornar a configuração permanente:**
    * Edite o arquivo `/etc/default/keyboard`.
    * Altere a linha `XKBLAYOUT="us"` para `XKBLAYOUT="br"`.
    * Altere a linha `XKBVARIANT=""` para `XKBVARIANT="abnt2"`.
    * Salve o arquivo e reinicie o sistema.

**Considerações Adicionais:**

* Caso você enfrente problemas com caracteres especiais, verifique se todas as atualizações do sistema estão instaladas.
* Em algumas versões do Kali Linux, pode ser necessário reiniciar a sessão ou o sistema para que as alterações tenham efeito completo.
* Existe um video no youtube que demonstra este processo de forma clara, caso necessite de ajuda visual.

**Informações importantes:**

* O layout ABNT2 é o padrão brasileiro e é essencial para a correta digitação de caracteres como "ç", acentos e outros símbolos.
* A configuração correta do teclado garante uma experiência de uso mais eficiente e produtiva no Kali Linux.
