# blog-preview-card
Hello this is Shaikh,
This project is a responsive Blog Preview Card component designed with a modern "Neo-brutalism" aesthetic. As a student at RUET, I developed this project to practice translating complex Figma designs into clean, functional code, focusing on layout precision and interactive user experiences.

Throughout the development of this card, I chose to use a div-based architecture for almost every element. I view divs as highly flexible boxes that can be shaped and manipulated with CSS to create any structure imaginable. By nesting children inside a primary .main-card parent, I established a clear hierarchy that was easy to manage. To keep the workflow organized, I prioritized semantic class naming, ensuring that both I and any other developer could easily identify and style specific sections like the header, body, and footer.For the hover effect i tell the browser to run this code if the user is using a device with a real mouse or trackpad by using @media (hover: hover)and (pointer: fine).So the hover wont work on mobiles.For the hover shadow effect i made a few changes from the original because it doesnt look nice to me for that reason i give a transition to make it look smoother and i liked it so i kept the change.

A key technical focus of this project was mastering the behavior of these boxes. I learned the importance of using properties like width: fit-content to prevent block-level elements from stretching unnecessarily. Furthermore, I focused on making the component truly responsive. I avoided using fixed pixel sizes for the main layout, as hard-coded values often break the design on different screen sizes. Instead, by utilizing max-width and percentage-based widths, I ensured the card remains "pixel-perfect" on a desktop while scaling gracefully for mobile users



