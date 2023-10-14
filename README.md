# Project Overview

This README provides an overview of a React app created using the command `npm create vite@latest`. The project structure, components, libraries, and key details are outlined below.

## Project Structure

The project structure is organized as follows:

- **Public Folder**
  - **Images**
  - **Fonts**

- **Src Folder**
  - **Components**
    - All components
      - With JSX and CSS files
    - **Pages**
      - Page that contains the component
    - **Utils**
      - Contains common files

- **App.jsx**
- **index.css**
- **main.jsx**

## Libraries and Dependencies

- **React-Scroll Library**
  - Used for smooth scrolling through the sections.
  - [Link to React-Scroll Library](https://www.npmjs.com/package/react-scroll)

## Development Details

- **Font Sizes**
  - All font sizes are given in `rem` units. When changing font sizes, ensure they are converted to `rem` for better consistency.

## Components

1. **Navbar**
   - Contains link tags to navigate to specific sections.

2. **Hero Section**
   - Includes a background image for better text visibility.
   - Responsive design is implemented.

3. **About Section**
   - A normal about section with text content and an image.

4. **Expertise Section**
   - Utilizes a JSON file in the `utils` folder to store data.
   - The `utils` folder is located in the `src` folder.

5. **Domains Section**
   - Also uses a JSON file in the `utils` folder to store data.
   - The `utils` folder is located in the `src` folder.

6. **Services Section**
   - Similarly, utilizes a JSON file in the `utils` folder for data storage.
   - The `utils` folder is located in the `src` folder.

7. **Testimonials Section**
   - Created using the Swiper JS library.
   - For more information on the library, refer to [Swiper JS](https://swiperjs.com/).
   - The component may use multiple arguments, so please check the documentation before making changes.

This README provides a clear overview of the project structure, components, and libraries used in the React app. It serves as a helpful reference for development and maintenance.
