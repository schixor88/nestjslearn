---
size: 16:9
class:
  - lead
  - invert
marp: true
footer: mail.kushagra.acharya@gmail.com | S4
paginate: true
---

# NestJS | 4

### Bootcamp

[Discord](https://discord.gg/URhAqbTEJb) | [Official Documentation](https://docs.nestjs.com/)

[Kushagra Acharya](https://www.linkedin.com/in/kushagraacharya/)

---

## Disclaimer

- This is an optional course and will not effect your academic credit
- If you're not interested and cannot fullfill any requirement or class rules you will be resulted for class dropout.

---

## General Rules

- Having a laptop and a separate notebook is compulsory
- Faliure to answer at least 3 viva question will result in dissmissal.
- Faliure to complete homework/classwork without any valid result will be unacceptable.

---

## Prerequisite

- Separate notebook/copy for notes
- NVM with Node Installed
- PC with VS Code Installed
- Stable Internet Connection

---

## Routing Decorators

---

## Decorators

- In your `app.controller.ts` file you can see some decorators
- `@Get()`
- `@Controller()`
- Decorators start with `@` and may or may not take arguments

---

## Routing Rules

- `@Conroller()` decorator can take argument to change routing routes
- `@Get()` decorator as well can take arguments to modify routing
- Run the project to test any routing changes in upcoming slides

---

## Get Route

```ts
@Controller()
export class AppController {
  @Get("/one")
  getRootRoute() {
    return "hey there!";
  }
}
```

- Test this change in your `localhost:3000/one`

---

## Controller Routing

```js
@Controller("/app")
export class AppController {
  @Get("/one")
  getRootRoute() {
    return "hey there!";
  }
}
```

- Figure out the endpoint for result 'hey there!'
- We can see that `controller routing` changes for all inner routes functions for higher level routing

---

## Task

- Create another method inside AppController as `getByeThere` which returns the string`'bye there'` with a get-decorater having argument as `'bye'`
- Test your output in localhost

---

# Run the application

- `npx ts-node-dev src/main.ts`

---

# Discussion

- Decorators
- Routing
- Arguments

---

# Congratulations

## Level Completed!

- Routing with Decorators
