# @libtommy2024/culpa-iusto-inventore-eum

## Install

Do not use it if you can use maps.

```sh
yarn add @libtommy2024/culpa-iusto-inventore-eum
```

or if npm is package manager of your choice

```sh
npm install @libtommy2024/culpa-iusto-inventore-eum --save
```

## Usage

### I want to create a new object

```js
import box from '@libtommy2024/culpa-iusto-inventore-eum';

const trackedObj = box({});
```

### I have an existing object

```js
import box from '@libtommy2024/culpa-iusto-inventore-eum';

const myObj = { 
  a: true,
  b: void 0,
};

const trackedObj = box(myObj);
// alternatively if you want to provide a custom orer
const trackedReversedObj = box(myObj, ['b', 'a']);
```

## LICENSE

[Apache License 2.0](https://github.com/libtommy2024/culpa-iusto-inventore-eum/blob/master/LICENSE)
