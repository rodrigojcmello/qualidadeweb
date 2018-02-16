# Qualidade Web

Boas práticas, e configurações de ambiente

## Contas do Projeto

- Nunca vincular uma conta ou e-mail pessoal ao projeto, o projeto precisa de um e-mail exclusivo no qual todos os serviços serão vinculados a ele.
- Criar uma planilha com todas as contas relacionadas ao projeto como: ssh, ftp, hospedagem, conta Google, conta Facebook, etc.
- Todas as senhas devem ser mudadas caso algum funcionário seja desligado do projeto.
- À respeito de redes sociais, sempre criar 2 páginas, uma para produção e outra para homologaço.

### Arquivo de Configuração

- Criar um config.js para armazenar todas as variáveis de configuração no projeto
- Nem sempre pode controlar tudo pelo config.js, às vezes há necessidades de outros arquivos (HTML, XML, etc) com diferentes configurações (homologação e produção), nesses casos é recomendado um sufixo \_prod ou \_dev (exemplo: "index_prod.html") para ajudar a identificar a finalidade desses arquivos.
- Em homologação o ambiente deve apontar para o banco de dados de homologação, as redes sociais de homologação e caso esteja tudo certo, subir a aplicação em homologação, ou seja, num ambiente que pessoas externas possam testar e liberar para produção. No caso de aplicativos, deve-se subir uma versão Beta.

# Estilo

### Ícones

- Criar uma conta no [Icons8](https://icons8.com.br/icon)
- Criar uma coleção com os ícones utilizados no projeto
- Baixar a fonte da coleção

> Nota: Fique atento ao idioma usado no Icons8, pois o Icons8 traduz os nomes dos ícones no css da fonte, tome cuidado para não adicionar itens à sua coleção em mais de um idioma ajudando então a manter a coerência.
