# Cypress Snippets for VSCode

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
| `dsb→` | describe   |
|  `it→` | it         |

### Mocha Expanded Snippets

`af` - after

```js
after(() => {
  $1; // Runs once after all of the individual tests
});

$0;
```

`afe` - afterAll

```js
afterAll(() => {
  $1; // Runs after each individual test
});

$0;
```

`bf` - before

```js
before(() => {
  $1; // Runs once before any of the individual tests
});

$0;
```

`bfe` - beforeEach

```js
beforeEach(() => {
  $1; // Runs before each individual test
});

$0;
```

`ctx` - context

```js
context('$1 Context name', () => {
  $0; // Add test cases
});
```

`dsb` - describe

```js
describe('$1', () => {
  $0; // Group tests by e.g. feature
});
```

`it` - it

```js
it('$1', () => {
  $0; // Add Cypress steps here
});
```
