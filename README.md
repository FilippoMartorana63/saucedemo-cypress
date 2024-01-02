# saucedemo cypress
 repositorio saucedemo cypress

 Teste End to End com Cypress em java script

O Cypress é uma ferramenta de automação de testes end-to-end que é fácil de usar. Aqui estão os passos básicos para realizar testes end-to-end com Cypress em JavaScript:

Instalação do Cypress: Inicie um novo projeto e instale o Cypress como dependência de desenvolvimento usando o seguinte comando no terminal:

npm install cypress --save-dev

Configuração do Cypress: Depois de instalado, podemos inicializar o Cypress usando o seguinte comando:

npx cypress open

Isso criará uma estrutura básica de diretórios e arquivos para os testes.

Escrevendo Testes: No diretório de testes gerado pelo Cypress, você encontrará exemplos de teste. Para criar um novo teste, crie um arquivo .spec.js e escreva seu código de teste usando a API do Cypress. Por exemplo:

describe('Meu Primeiro Teste', () => {
  it('Deve visitar a página e verificar o conteúdo', () => {
    cy.visit('https://www.saucedemo.com');
    cy.contains('Login-Produtos');
  });
});
Executando Testes: Execute seus testes usando o comando:

npx cypress run

Ou, se estiver usando a interface gráfica do Cypress:

npx cypress open

Isso abrirá a interface do Cypress, onde você pode executar seus testes interativamente.




