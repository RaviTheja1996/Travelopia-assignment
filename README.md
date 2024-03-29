# Travelopia-assignment

## Description

This is a full-page component built for a specific problem statement which contains a header, footer and main area consisting of an image and an overlay over it with a title and a button below it which upon clicking display a "Hello, world" alert.

## Tech Stack

1. HTML
2. CSS
3. Javascript

## Coding Overview

1. I have used semantic elements to define the header, footer and main area's in the webpage as it is supported by HTML5 standards and also provides accessibility to screen readers and other supportive tech.
2. I have used display value as "flex" for the header and footer to style them as horizontal lists and center the content present in header and footer.
3. For the main area in the page, I have used a section tag to render the hero part of the page which consists of the image, overlay, title and button, to achieve the desired layout as per problem statement I have given the hero section position as "relative" and divided the children into two parts one being image and second part containing the title and button. these parts have a position of "absolute" and I have provided appropriate top,left,right values to them to center the second part.
4. For rendering the image I have used the "img" tag rather than using css to set it as per problem statement.
5. For optimizing the image to different screen sizes I have used the css of display as "block" and max-width as "100%" and left the height to default value of auto.
6. For the overlay implementation I have used the pseudo-element "::after" and applied opacity to the image.
7. For implementing the alert functionality of the button I have used the "alert()" method from javascript to display an alert of "Hello, World."

## screenshots

![Screenshot 1](./screenshots/Screenshot-01.png)
![Screenshot 4](./screenshots/Screenshot-04.png)
![Screenshot 2](./screenshots/Screenshot-02.png)
![Screenshot 3](./screenshots/Screenshot-03.png)

## Deployment

live site : [link](https://travelopia-assignment-eight.vercel.app/)
