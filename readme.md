# Create Your Notes

**Create Your Notes** is a simple web-based notes application that allows users to create, edit, save, and delete notes directly in the browser. The app uses **localStorage** to persist notes, so they remain available even after refreshing or reopening the page.

This project was built using **HTML, CSS, and JavaScript** and focuses on DOM manipulation and client-side data storage.

---

## Features

- Create multiple notes dynamically  
- Edit notes directly using contenteditable elements  
- Delete notes with a single click  
- Notes are automatically saved using localStorage  
- Clean and simple user interface  

---

## Technologies Used

- **HTML** – Page structure and layout  
- **CSS** – Styling, gradients, and responsive design  
- **JavaScript** – DOM manipulation, event handling, and localStorage  

---

## How It Works

1. The user clicks the **Create Notes** button  
2. A new editable note element is created dynamically  
3. Notes can be typed and edited directly  
4. Notes are automatically saved to localStorage  
5. Clicking the delete icon removes the note and updates storage  

---

## Personal Reflection

### What this project is  
This project is a browser-based notes application that allows users to write and manage notes without needing a backend. It demonstrates how localStorage can be used to store and retrieve user data on the client side.

### Why I made it  
I created this project to better understand how to manipulate the DOM dynamically and how data persistence works in front-end applications. I wanted to build something practical that users could actually use in everyday situations.

### How I made it  
I started by designing the layout using HTML and CSS. Then, I used JavaScript to create notes dynamically when the user clicks a button. I implemented localStorage to save the notes by storing the container’s HTML and loading it again when the page refreshes. Event listeners were added to handle editing and deleting notes.

### What I struggled with  
One of the main challenges was ensuring that notes were saved correctly every time the user edited or deleted them. Handling events on dynamically created elements also required careful logic to avoid bugs.

### What I learned  
Through this project, I learned:
- How to use localStorage for data persistence  
- How to work with dynamically created DOM elements  
- How event delegation works  
- How to build interactive features without a backend  
- How small UX decisions impact usability  


---

This project helped me strengthen my understanding of JavaScript fundamentals and front-end application behavior.
