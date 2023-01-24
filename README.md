# Projeto de automação de testes com codeceptjs e appium

## Inicialização do projeto:
npm init

## Instalação do codeceptjs na pasta do projeto:
npm install codeceptjs webdriverio --save

## Inicialização do codeceptjs:
npx codeceptjs init

## Capabilities
Os campos appPackage e appActivity é obtido com o desenvolvedor

## Gerar outra class de teste
npx codeceptjs gt

## Gerar Page Object
npx codeceptjs gpo

## Comandos para rodar a automação dos testes
npx codeceptjs run --steps (vai executar todos os testes com o final _tests.js)
npm run test

## Configuração de informações randômicas via NPM
npm install node-random-name
npm install random-number

## Instalação do driver para rodar testes em browser
appium --allow-insecure chromedriver_autodownload



## Referenciar o formato dos campos ao mapear
. -> class
# - > id
~ -> acessibility id