# Portfolio Website

This is a portfolio website template built using Vite, React, and TypeScript. It's designed to showcase your projects, skills, and experience in a clean and responsive manner. The use of Vite ensures fast development and efficient bundling, while TypeScript provides static typing for a more robust codebase.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Folder Structure](#folder-structure)
  - [Customization](#customization)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [License](#license)

## Features

- **Vite:** Utilizes Vite for a fast and efficient development experience.
- **TypeScript:** Written entirely in TypeScript for static typing and enhanced code quality.
- **Responsive Design:** Ensures a seamless experience across various devices and screen sizes.
- **Project Showcase:** Display your projects with details such as descriptions, technologies used, and project links.
- **Skills Section:** Highlight your skills and proficiency in various technologies.
- **Contact Form:** Include a contact form for visitors to get in touch with you easily.
- **Dark Mode:** Toggle between light and dark mode for improved user experience.

## Getting Started

### Prerequisites

Make sure you have Node.js and npm installed on your machine.

### Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/portfolio.git
    ```

2. Navigate to the project folder:

    ```bash
    cd portfolio
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

## Usage

### Folder Structure

The project structure is organized as follows:

- `src/`: Contains the source code of the website.

  -  `Assets`: Store static data 
  - `components/`: Reusable components Atomic Design.
      - `Atoms`
      - `Molecules`
      - `Organisms`
      - `Templates`
      - `Pages`
  - `styles/`: Stylesheets for the project.
  - `utils/`: Utility functions and helpers.
- `public/`: Static assets such as images and fonts.

### Customization

1. **Personal Information:**
    - Open `src/data/profile.ts` and update the information with your details.
   
2. **Projects:**
    - Add your projects to `src/data/projects.ts`.

3. **Skills:**
    - Update your skills in `src/data/skills.ts`.

4. **Contact Form:**
    - Connect the contact form to your preferred backend service. Update the `handleSubmit` function in `src/Compoent/pages/Contact.vue`.

5. **Styling:**
    - Customize the styles in `src/styles`.

## Deployment

To build and deploy the website, run:

```bash
npm run build
```
This will generate a dist folder containing the optimized and minified assets. Upload the contents of this folder to your hosting provider.

Technologies Used
Vite
TypeScript
License
This project is licensed under the MIT License - see the LICENSE file for details.