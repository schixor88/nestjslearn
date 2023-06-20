---
size: 16:9
class:
  - lead
  - invert
marp: true
footer: mail.kushagra.acharya@gmail.com | S3
paginate: true
---

# NestJS | 3

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

## Setup and Modification

---

## Extensions

Install the following in VSCode

- [NestJS](https://marketplace.visualstudio.com/items?itemName=ashinzekene.nestjs)

- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

---

## Structuring

- Currently we have all our classes in a single file
- This is not a very good approach for development
- We will now extract the app controller and the app module to a separate file

---

# Before that: Conventions

![width:1000px height:500px](n3_convention.png)

---

# Creating files

- Create `app.controller.ts` file
- Move your `AppController class` to this file
- Fix any imports if necessary
- Do the same for `AppModule class` in `app.module.ts` file

---

# main.ts

- The `main.ts` file should now only contain the `bootstrap()`
- But you will need to fix the import for `AppModule` in _main.ts_ as it is being used as `NestFactory.create(AppModule)`

---

# Run the application

- `npx ts-node-dev src/main.ts`

---

# Discussion

- Importance of naming conventions
- What is separation of concern
- Help in project structuring
- Project scalability

---

# Congratulations

## Level Completed!

- Structuring for files and naming
