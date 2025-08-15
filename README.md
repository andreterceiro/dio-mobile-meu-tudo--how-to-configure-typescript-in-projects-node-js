# Installation

Remember that your code will be transpilled, so you can install type script using the flag '-D':

```
npm install -D typescript
```


# Type inference

TypeScript can know the type of a variable by inference.

![inference](images/type-inference.png)

And as you can see in the previous image, one type a type is infered, it can be changed. In other words, you can't pass as example a number to a string variable (do not mind if the type was inferred).


# npx tsc

You can execute a transpilation process through tsc, as example:

```
npx tsc src/index.ts
```

Will be created the file index.js in the directory 'src'.


# Teacher suggestion to do the transpilation and execution process with only one command

![reacher suggestion](images/teacher-suggestion.png)

OBS: From the previous image the teacher executed the command `npm run start:dev`.


# Generating tsconfig

```
npx tsc --init
```
