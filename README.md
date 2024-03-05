# TodoWebApp
Welcome to our web project! This project is a sleek, functional web application designed to showcase the powerful combination of HTML, CSS, JavaScript, JSTL, and the robust Spring Boot framework. Whether you're looking to manage tasks, display dynamic content, or just explore the capabilities of modern web development, you've come to the right place!

## Technologies Used

- **HTML (Hyper Text Markup Language):** The backbone of our web pages. We use standard tags like `<html>`, `<head>`, `<body>`, and `<table>` to structure our content.
- **CSS (Cascading Style Sheets):** Our web pages are styled with CSS to look visually appealing. We've also integrated the Bootstrap CSS framework for that extra polish and responsiveness.
- **JavaScript:** Adds interactivity to our web pages. For instance, we use the Bootstrap Datepicker for a smooth date selection experience.
- **JSTL (JavaServer Pages Standard Tag Library):** We use JSTL to dynamically display data on our web pages. The <c:forEach> tag is a workhorse in looping through items like todos.
- **Spring Form Tag Library:** Makes handling form elements a breeze, especially with its data binding-aware tags.

## Architecture

- **DispatcherServlet (Front Controller):** The heart of our application, routing all requests through a central controller to ensure a seamless flow.
- **Model-View-Controller (MVC):** Our application adheres to the MVC pattern, separating the logic of handling data (Model), user interface (View), and control flow (Controller) for cleaner, more manageable code.
- **Spring Boot Starters:** To get our app off the ground quickly, we leveraged several Spring Boot Starters, including:
- **Spring Form Tag Library:** Makes handling form elements a breeze, especially with its data binding-aware tags.
  - **Spring Boot Starter Web:** For building web, including RESTful, applications using Spring MVC.
  - **Spring Boot Starter Validation:** For validating input data.
  - **Spring Boot Starter Security:** For securing our application.
  - **Spring Boot Starter Data JPA:** For database integration using Java Persistence API.

### Getting Started

To get this project up and running on your local machine, you'll need to have Java and Maven installed. Simply clone this repository, navigate to the project directory, and run:

```
mvn spring-boot:run
```

## Images
![image](https://github.com/utkarshsinh/TodoWebApp/assets/107430204/6b768c16-c740-4aab-8256-58908d864f09)

![image](https://github.com/utkarshsinh/TodoWebApp/assets/107430204/132a9fe0-2686-4478-895e-a266a4fdc641)


