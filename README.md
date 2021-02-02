# Importing a shared lib into an app

## The problem

I've set up a nextjs application and a shared component lib that uses typescript.

In my index.ts file within the shared lib I've exported a component as well as a typescript interface.

However, when running the application, the following error crops up:

```
Attempted import error: 'SharedComponentsProps' is not exported from './lib/shared-components'.
```

## Reproduction

```
yarn install
yarn nx run testnext:serve
```
