
# AI Image Generation using DALL-E AI in MERN Stack - Frontend Implementation

This project is an AI Image Generation application that employs the powerful DALL-E AI model. It is skillfully integrated into the MERN (MongoDB, Express.js, React.js, Node.js) stack, providing users with a user-friendly interface to generate captivating images from textual prompts. Immerse yourself in the world of AI-driven creativity and witness the magic of turning simple text into stunning visual art.
## Overview:

The frontend of the application is built using React.js, a popular JavaScript library for building user interfaces. It utilizes React Router for managing the application's routing and navigation. The application features a simple layout with a header containing the logo and a "Create" button for users to generate new images.

## Implementation:

### Header:
The header section is designed to display the logo of the application and a "Create" button using flexbox for proper alignment. The logo image is imported from the 'assets' directory and displayed as a clickable link to the home page.

### Routing:
React Router is used to handle the application's routing. The BrowserRouter component wraps the entire application, and different Routes are defined for the home page and the create-post page. When users click on the "Create" button, they are redirected to the create-post page.

### Main Content:
The main content area is implemented as a container with padding and a background color. The min-height property is set to ensure that the container takes up the full height of the viewport, leaving space for the header.

### Home and CreatePost Pages:
The Home and CreatePost components are defined and rendered based on the corresponding Routes. The Home component represents the home page of the application, while the CreatePost component is responsible for handling the image generation process.

## Usage:

### Installation:
Ensure you have Node.js and npm installed on your system.

### Clone the Repository:
Clone the project repository to your local system:

```bash
git clone https://github.com/your-username/ai-image-generation.git
