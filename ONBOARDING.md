# Guia do Projeto de Empacotamento Debian

Estamos felizes em tê-lo(a) a bordo! Este guia foi elaborado para ajudá-lo(a) a dar os primeiros passos no mundo do empacotamento Debian, fornecendo recursos essenciais e orientações práticas.

## O que é o Empacotamento Debian?

Empacotar no Debian significa criar pacotes que permitem que softwares sejam instalados, atualizados e removidos de forma eficiente em sistemas Debian. O processo envolve a criação de arquivos de controle, scripts de instalação e a configuração adequada para garantir que o software funcione corretamente dentro do ecossistema Debian.

Para uma introdução detalhada, consulte o guia [Empacotamento 101](https://debianbrasil.org.br/pt-br/empacotamento/empacotamento-101).

## Preparando seu Ambiente

Antes de começar, é importante configurar seu ambiente de desenvolvimento:

1. **Instale as ferramentas necessárias**:
   ```bash
   sudo apt update
   sudo apt install build-essential devscripts lintian
   ```

2. **Configure seu ambiente Git**:
   ```bash
   git config --global user.name "Seu Nome"
   git config --global user.email "seuemail@example.com"
   ```

3. **Crie uma conta no Salsa**:
   Acesse [https://salsa.debian.org](https://salsa.debian.org) e crie uma conta. O Salsa é a plataforma de hospedagem de código do Debian.(Cada conta criada tem que ser aprovada manualmente, o que leva em tono de 2 á 5 dias, caso sua conta seja rejeitada tente criar denovo e entre em contato com outros membros da Debian-Brasil para te ajudar)

4. **Familiarize-se com o `git-buildpackage`**:
   Esta ferramenta facilita o processo de construção de pacotes Debian a partir do código-fonte.

## Recursos de Aprendizado

- **Guia Oficial de Empacotamento**: [https://debian-handbook.info/browse/pt-BR/](https://debian-handbook.info/browse/pt-BR/)
- **Debian Policy Manual**: [https://www.debian.org/doc/debian-policy/](https://www.debian.org/doc/debian-policy/)
- **Debian New Maintainers' Guide**: [https://www.debian.org/doc/manuals/maint-guide/](https://www.debian.org/doc/manuals/maint-guide/)

## Como Contribuir

1. **Escolha um pacote**: Consulte a lista de pacotes que precisam de manutenção ou que você gostaria de empacotar.

2. **Crie um fork**: No Salsa, faça um fork do repositório do pacote escolhido.

3. **Empacote o software**: Siga as diretrizes do Debian para criar o pacote.

4. **Submeta uma Merge Request**: Após empacotar, submeta uma Merge Request para revisão.

5. **Revisão e Upload**: Um mantenedor revisará seu pacote e, se aprovado, fará o upload para os repositórios oficiais do Debian.

Para detalhes completos, consulte o guia [Empacotamento 101](https://debianbrasil.org.br/pt-br/empacotamento/empacotamento-101).

## 💬 Como Entrar em Contato

Se tiver dúvidas ou precisar de ajuda, entre em contato com os membros do Debian-Brasil:

- **IRC**: Canal `#debian-mentors` na rede [OFTC](https://www.oftc.net/)
- **Matrix**: Sala `#debian-mentors:matrix.org`
- **Lista de Discussão**: [debian-mentors@lists.debian.org](https://lists.debian.org/debian-mentors/)


