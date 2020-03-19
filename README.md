## Name Generator, with Fruit!

Based on the Docker container [name generator](https://github.com/moby/moby/blob/master/pkg/namesgenerator/names-generator.go), but with fruit.

Returns a name and a fruit or vegetable.

Has an optional `safe` mode that contains no punctuation or spaces.

### Install

```
npm install fruitname
```

### Usage

```
const fruitname = require('fruitname');

const name = fruitname();

console.log(name)

// Dijkstra's Potato
```

Safe Mode

```
const fruitname = require('fruitname');

const name = fruitname({safe: true});

console.log(name)

// dijkstras_potato
```
