# kabug-rb
Repositório do projeto Kabug com Cucumber, Capybara e Ruby

## Como executar o projeto

* Importante ter o Ruby instalado (versão 2.5 ou superior)

### Instalar o Bundler
`
gem install bundler
`
### Instalar as dependências do Ruby (projeto)
`
bundler install
`
### Executar localmente (minha maquina)
`
bundle exec cucumber
`
### Executar no servidos de CI (gerando reposts JSON)
`
bundler exec cucumber -p ci
`