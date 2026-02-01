# json-based-dsl-architect

This project provides json based dsl langvich for architect designers. This interactive tool lets you edit JSON data vs live to visualize your data.

Internally the data is actually stored as a list of key/value pairs, not as an object. When changes are made to the data through the editor on the left, or through the modal, they first go to this data structure which acts as the "single source of truth". From there changes are propogated to other parts of the program to stay in sync.

## Installation

Start by running `npm install` to install all necessary dependencies.
`npm run dev` runs the app in the development mode.

## STACK:
### Svelte 5
### Typescript
### Monaco Editor
### GoJS lib
