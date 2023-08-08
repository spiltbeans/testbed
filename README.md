# testbed

Sometimes I want a convenient way to just run some code with little setup

## How to use

This project is set up to be a monorepo that has multiple different code environments

```
packages
-- react-tb: React, TypeScript, testbed
-- js-html: JavaScript, HTML testbed
-- next-app: Next App router test bed
```

Each environment is managed by `pnpm`.

Get started by navigating to the project root and running the command

```
pnpm i
```

To start a specific project, you can run the command

```
pnpm --filter <project name> <command>
```

Example to start react testbed

```
pnpm --filter react-tb start
```
