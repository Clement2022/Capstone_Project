# Capstone_Project: Study App

## Project Overview

I will be building a study app that will help both the teachers and students. It's projected to be a minimum available product. It is all about how the app understands the user's interest in different products or services. It is an advanced feature that an app offers the user to work anywhere an internet connection is available. It will also track their due dates and completed projects/homework. The app will help organize and manage their resources during research. With the help of this feature, teachers can share different types of resources such as images, videos, pdf, books, articles, etc. It ultimately helps students to get the maximum benefit from this app.

---

## Functionality

### User Stories

- "As a user l want my account and information to **remain secure**."

- "As a user l want to be able to **create, add and delete** projects."

- "As a user l want to be able to **view all the projects and track** their due dates."

- "As a user l want to be able to **manage and organize** resources for research projects."

- "As a user l want to be able to perform all the above Info and able to search dictionary, books, media all in a single dashboard by making a simple **API Calls**."

### Backend Functionality

1. Implementing login authentication to protect user profile & create by redirecting to login and registered page.

2. Use the form to create register, login/out page that will allow the user to create and add projects.

3. User the form to create a view function that will receive the user submissions and organize the resources, whether it is a book, video or an article.

### Additional Features:

- Making API Calls

---

## Data Models

<table><tr><td width="400px" valign="top">

```ts
Resources Model
    name = (CharField)
    author = (CharField)
    date_published = (DateField)
    resources_type = (CharField)
    url = (CharField)
    price = (DecimalField)
    projects = (ManyToManyField)
```

</td><td width="400px" valign="top">

```ts
Project Model
    user = (ForeignKey)
    name = (CharField)
    due_date = (DateField)




```

</td></tr></table>

---

## Schedule

### First Week:

- [x] Create Repository, Setup and Clone.
- [x] Readme.md.
- [x] Planning on Database Structure.
- [ ] Set up User model.
- [ ] Create register and login urls and views.
- [ ] Create/style forms to register/login users.
- [ ] Set up Project and Resource models.
- [ ] Create a Project and a Resource in the admin panel and associate the Resource with the Project.
- [ ] Bootstrap, CSS Stylings & Adjustments.

---

### Second Week:

- [ ] Create a url and a view for listing all of a user's.
- [ ] Create a url, view and form to create new Projects.
- [ ] Developing Backend Reactions.
- [ ] Projects, style the projects on the template.
- [ ] Create a url, view and template for viewing the details of a Project.
- [ ] The Project's resources will also be listed on this page.
- [ ] Style Project detail page and resources list.
- [ ] Create a form on the Project detail page for adding additional resources to the project

---

### Final Week:

- [ ] Bootstrap, CSS Stylings & Adjustments.
- [ ] Presentation
- [ ]
- [ ]

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

- "As a user l want to be able to **click on task button** when the task is complete. E.g., To-Do List, Projects, & Homework’s. All completed tasks will not show on to-do list"

## Problems Encounter:

- Naming my models and the fields that the model will inherit.
- Finding what to JS in the project.
