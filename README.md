# Mocha - Cypress - Chai Snippets for VSCode

- [Mocha - Cypress - Chai Snippets for VSCode](#mocha---cypress---chai-snippets-for-vscode)
  - [Mocha Snippets](#mocha-snippets)
  - [Cypress Snippets](#cypress-snippets)
  - [Chai Snippets](#chai-snippets)

This extension adds snippets for Cypress.\
Helps writing tests easy and fast.

## Mocha Snippets

|         Snippet | Example                                        |
| --------------: | ---------------------------------------------- |
|     `@describe` | `describe('description', () => { ... });`      |
|      `@context` | `context('description', () => { ... });`       |
|           `@it` | `it('description', () => { ... });`            |
|       `@before` | `before(() => { ... });`                       |
|   `@beforeEach` | `beforeEach(() => { ... });`                   |
|        `@after` | `after(() => { ... });`                        |
|    `@afterEach` | `afterEach(() => { ... });`                    |
| `@describeOnly` | `describe.only('description', () => { ... });` |
| `@describeSkip` | `describe.skip('description', () => { ... });` |
|       `@itOnly` | `it.only('description', () => { ... });`       |
|       `@itSkip` | `it.skip('description', () => { ... });`       |

## Cypress Snippets

|     Snippet | Example                                          |
| ----------: | ------------------------------------------------ |
|    `@visit` | `cy.visit('url');`                               |
|      `@get` | `cy.get('selector')`                             |
| `@contains` | `cy.contains('text')`                            |
|     `@wait` | `cy.wait(time);`                                 |
| `@viewport` | `cy.viewport('width', height);`                  |
|  `@request` | `cy.request('url').then((response) => { ... });` |
| `@scrollTo` | `cy.scrollTo('position', { ... });`              |

## Chai Snippets

|                Snippet | Example                                    |
| ---------------------: | ------------------------------------------ |
|       `@shouldVisible` | `should('be.visible')`                     |
|    `@shouldNotVisible` | `should('not.be.visible')`                 |
|   `@shouldContainText` | `should('contain.text', 'text')`           |
|     `@shouldHaveClass` | `should('have.class', 'className')`        |
|        `@shouldHaveId` | `should('have.id', 'id')`                  |
|      `@shouldHaveAttr` | `should('have.attr', 'attrName', 'value')` |
|     `@shouldHaveValue` | `should('have.value', 'value')`            |
|     `@shouldBeChecked` | `should('be.checked')`                     |
|  `@shouldNotBeChecked` | `should('not.be.checked')`                 |
|    `@shouldBeDisabled` | `should('be.disabled')`                    |
| `@shouldNotBeDisabled` | `should('not.be.disabled')`                |
|         `@shouldExist` | `should('exist')`                          |
|      `@shouldNotExist` | `should('not.exist')`                      |
|       `@shouldBeEmpty` | `should('be.empty')`                       |
|    `@shouldNotBeEmpty` | `should('not.be.empty')`                   |
|       `@shouldHaveCss` | `should('have.css', 'property', 'value')`  |
