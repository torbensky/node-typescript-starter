# node-typescript-starter

A basic starter template for Node + Typescript

This is pretty minimal. Only `typescript` and `ts-node` development dependencies which I feel are pretty essential to any Node + Typescript project.

## Development

- `npm run build` to compile TS -> JS. This is configured to incrementally compile files in `src` output to `dist`.
- `npm run watch` to compile files in `src` to `dist`, watching for any changes and incrementally rebuilding whenever file changes are made in `src`
- `npm run clean` to remove `dist`

## Running

`npm run start`

- uses `ts-node` to run the entrypoint `src/index.ts`.

## Using GitHub Template

This repository is a GitHub [Template Repository](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/)

You can quickly [use this Template to create a new Node + Typescript project of your own](https://help.github.com/en/articles/creating-a-repository-from-a-template)
