# Cypress Snippets for VSCode

This extension adds snippets for Cypress.\
Helps writing tests easy and fast.

## Snippets

| Prefix | Example    |
| -----: | ---------- |
|  `be→` | before     |
| `bfe→` | beforeEach |
|  `dsb` | describe   |
|   `it` | it         |

### Expanded Snippets

`before`

```js
before(() => {
  //Runs once before any of the individual tests;
});
```

`beforeEach`

```js
beforeEach(() => {
  //Runs before each individual test;
});
```

`it`

```js
it('Test case name', () => {});
```
