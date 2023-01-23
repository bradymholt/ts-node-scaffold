# ts-node-scaffold

A scaffold for writing scripts in TypeScript and running them in Node.js.

With this scaffold, you run run `./main.ts` to run the `main.ts` TypeScript script.  No intermediate `tsc` step or package.json scripts needed.  [ts-node](https://typestrong.org/ts-node/) with a shebang is being used to simplify execution.

### Original Setup
When creating this scaffold, I ran these commands:

```
npm init
npm install typescript ts-node
npx tsc --init
touch main.ts && chmod +x main.ts
```
