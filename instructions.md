# Lab 01: Building a Simple Web Page Using Bootstrap (CDN)

## Objective
Learn how to use Bootstrap via CDN to enhance the appearance of a static web page.

---

## Background
Bootstrap is a CSS framework that allows developers to quickly design responsive and visually appealing web pages. When used via CDN, it is loaded from an external server instead of being installed locally.

---

## Task 1: Setup a Basic Page

Create an `index.html` file and add the following code:

```html
<!DOCTYPE html>
<html>
<head>
  <title>My First Bootstrap Page</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="container mt-4">

  <h1 class="text-primary">Welcome</h1>
  <p>This is a simple static web page using Bootstrap.</p>

</body>
</html>
```

---

## Task 2: Modify the Page

Enhance the page by adding:

- A **button**
- A **card component**
- A **two-column layout** using Bootstrap grid

---

## Task 3: Create a Student Profile Page

Convert the page into a simple **Student Profile Page** containing:

- Name  
- Program  
- Short bio  
- A profile card layout  

---

## Reflection Questions

Answer the following:

1. Is your web page static or dynamic? Why?  
2. What is the role of the Bootstrap CDN link?  
3. What will happen if the CDN is not accessible?  

---

## Submission Guidelines

- Submit your work via GitHub Classroom (repository already created for you)
- Modify the provided `index.html` file

### Commit Requirements

You must make at least **3 meaningful commits**:

1. Initial setup (basic HTML structure)
2. Adding Bootstrap (CDN + styling)
3. Final version (components like button, card, layout)

Each commit should reflect a clear step in your progress.

---

**Note:** Submissions with a single final commit may receive reduced marks.
---

## Optional Challenge

Try removing Bootstrap and observe how the page changes.