# ts-cli

Typescript cli repo sample to run scripts

# Dependencies

- [Node](https://nodejs.org/en/download)

# Setup

```shell
npm i
npm run start
```

# Passing arguments

If you need to pass arguments to the script you have can simply add them in the command line:

```shell
npx ts-node src/main.ts arg1 arg2
```

OR

```shell
npm run start arg1 arg2
```

Then in the code you can access them using `process.argv`:

```typescript
const arg1 = process.argv[2]
const arg2 = process.argv[3]
```
