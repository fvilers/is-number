# @fvilers/is-number

A TypeScript type guard that validates if the given value is a string

## Installation

```
npm install @fvilers/is-number
```

or

```
yarn add @fvilers/is-number
```

## Usage

```ts
import isNumber from "@fvilers/is-number";

const variable: any = 42;

if (isNumber(variable)) {
  // From here, variable is strongly typed as a number
  console.log(
    "Variable is a number with an exponential value of",
    variable.toExponential(10)
  );
} else {
  console.log("Variable is not a number");
}
```

It will output:

```
Variable is a number with an exponential value of 4.2000000000e+1
```
