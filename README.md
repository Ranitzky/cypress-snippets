# Mocha & Cypress Snippets for VSCode

- [Mocha \& Cypress Snippets for VSCode](#mocha--cypress-snippets-for-vscode)
  - [Mocha Snippets](#mocha-snippets)
  - [Cypress Snippets](#cypress-snippets)
  - [Mocha Expanded Snippets](#mocha-expanded-snippets)
    - [`af` - after](#af---after)
    - [`afe` - afterAll](#afe---afterall)
    - [`bf` - before](#bf---before)
    - [`bfe` - beforeEach](#bfe---beforeeach)
    - [`ctx` - context](#ctx---context)
    - [`dsc` - describe](#dsc---describe)
    - [`it` - it](#it---it)
  - [Cypress Expanded Snippets](#cypress-expanded-snippets)
    - [`cyg` - get](#cyg---get)
    - [`cyv` - visit](#cyv---visit)
    - [`cyreq` - request](#cyreq---request)
    - [`cyvp` - viewport](#cyvp---viewport)
    - [`cywt` - wait](#cywt---wait)

This extension adds snippets for Cypress.\
Helps writing tests easy and fast.

## Mocha Snippets

| Prefix | Example    |
| -----: | ---------- |
|  `af→` | after      |
| `afe→` | afterEach  |
|  `bf→` | before     |
| `bfe→` | beforeEach |
| `ctx→` | context    |
| `dsc→` | describe   |
|  `it→` | it         |

## Cypress Snippets

| Prefix | Example |
| -----: | --------
| `cyg→` | get |
| `cyv→` | visit |
| `cyreq→` | request |
| `cyvp→` | viewport |
| `cywt→` | wait |

## Mocha Expanded Snippets

### `af` - after

```js
after(() => {
  $1; // Runs once after all of the individual tests
});

$0;
```

### `afe` - afterAll

```js
afterAll(() => {
  $1; // Runs after each individual test
});

$0;
```

### `bf` - before

```js
before(() => {
  $1; // Runs once before any of the individual tests
});

$0;
```

### `bfe` - beforeEach

```js
beforeEach(() => {
  $1; // Runs before each individual test
});

$0;
```

### `ctx` - context

```js
context('$1 Context name', () => {
  $0; // Add test cases
});
```

### `dsc` - describe

```js
describe('$1', () => {
  $0; // Group tests by e.g. feature
});
```

### `it` - it

```js
it('$1', () => {
  $0; // Add Cypress steps here
});
```

## Cypress Expanded Snippets

### `cyg` - get

```js
cy.get('$1');$0
```

### `cyv` - visit

```js
cy.visit('$1');$0
```

### `cyreq` - request

```js
cy.request({
  method: '$1',
  url: '$2',
  headers: { $3 },
  body: { $4 },
});
$0
```

### `cyvp` - viewport

```js
cy.viewport($1);$0
```

### `cywt` - wait

```js
cy.wait($1);$0
```
