# Capstone_Project: Study App

## Project Overview

---

I will be building an app that will help both teacher and students all together. It is all about how much an app understands the users who are looking out for different products or services. This is the advanced feature that an app offers the user to work anywhere an Internet connection is available. It will also track their due dates and completed project/homework. The app will help organize and manage their resources during research. With the help of this feature, teachers can share different types of multimedia content such as images, videos, pdf, etc. It ultimately helps students to get the maximum benefit from the session.

---

## Functionality

---

### User Stories

- "As a user l want my account and information to **remain secure**."

- "As a user l want to be able to **create, add and delete** projects."

- "As a user l want to be able to **view all the projects and track** their due dates."

- "As a user l want to be able to **manage and organize** resources for research projects."

- "As a user l want to be able to perform all the above Infor and able search dictionary, books, media all in a single dashboard by making a simple **API Calls**."

### Backend Functionality

1. Implementing login authentication to protect user profile & create by redirecting to login and registered page.

2. Use the form to create register, login/out page that will allow the user to create and add projets.

3. Create a view that receives the user submissions from the form and show it on frontend.

### Additional Features:

- Making API Calls

---

## Data Models

---

<table><tr><td width="400px" valign="top">
```ts
     Resources Model
     name = (CharField)
     author = (Char Field)
     date_published = (DateField)
     url = (Char Field)
     price = (Decimal Field)
     projects = (ManyToManyField)
```
</td><td width="600px"><br>

```ts
Project Model
     name = (CharField)
     user = (ForeignKey)
     due_date = (DateField)
```

</td></tr></table>
- Project Model
    - name = (CharField)
    - user = (ForeignKey)
    - due_date = (DateField)

- Resources Model
  - name = (CharField)
  - author = (Char Field)
  - date_published = (DateField)
  - url = (Char Field)
  - price = (Decimal Field)
  - projects = (ManyToManyField)

---

## Schedule

---

### First Week:

- [x] Create Repository, Setup and Clone.
- [x] Readme.md
- [x] Planning on Database Structure
- [ ] Create my env (Visual Environment)
- [ ] Start building Capstone Project
- [ ] Creating My models
- [ ] Botstrap, CSS Stylings & Adjustments.

---

### Second Week:

- [ ] Developing Backend Reations.
- [ ] Work on Setting up Functions.
- [ ] Botstrap, CSS Stylings & Adjustments.

---

### Final Week:

- [ ] Developing Frontend Operations.
- [ ] Connecting Frontend to the Backend.
- [ ] Botstrap, CSS Stylings & Adjustments.
- [ ] Presentation

---

## Capstone Requirement:

- Python
- HTML
- CSS Stylings
- Django
- JavaScript

---

## Extra Feature:

- "As a user l want to be able to **create a study** card for the course."
  <br/>
  <br/>
- "As a user l want to be able to **click on task button** when the task is complete. E.g., To-Do List, Projects, & Homework’s. All completed tasks will not show on to-do list"
  <br/>
  <br/>

## Problems Encounter:

- Naming my models and the fields that the model will inherit.
