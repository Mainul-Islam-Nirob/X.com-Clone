# X.com Clone

This project is a clone of X.com, built using Tailwind CSS and HTML. The goal is to recreate the visual design and basic functionality of X.com, leveraging the utility-first CSS framework Tailwind CSS.

## Table of Contents

- [Introduction](#introduction)
- [Live Site](#Live-Site)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)


## Introduction

The X.com Clone project aims to replicate the appearance and core components of X.com. It serves as a practice project for using Tailwind CSS to build modern, responsive web interfaces.

## Live Site
[See the Result](https://mainul-islam-nirob.github.io/X.com-Clone/)

## Features

- **Responsive Design**: The layout is fully responsive, ensuring compatibility across various devices and screen sizes.
- **Sticky Navigation**: Sticky elements that remain in view as the user scrolls.
- **Interactive Components**: Includes interactive components like search bars and trend items.

## Installation

To get started with this project, follow the steps below:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/x-com-clone.git
   cd x-com-clone
   ```
2. **Install dependencies**:
   This project uses [Tailwind CSS](https://tailwindcss.com/). Ensure you have [Node.js](https://nodejs.org/) installed, then install Tailwind CSS via npm:

   ```bash
   npm install
   ```
3. **Build Tailwind CSS**:

   ```bash
   npx tailwindcss build src/styles.css -o dist/styles.css
   ```
4. **Open `index.html` in your browser**:
   Simply open the `index.html` file in your browser to view the project.

## Usage

After completing the installation steps, you can start using and modifying the project. Tailwind CSS classes are used extensively to style the components. Feel free to adjust the HTML and CSS to meet your needs.

## Project Structure

```plaintext
x-com-clone/
├── dist/
│   └── styles.css         # Compiled Tailwind CSS
├── src/
│   └── styles.css         # Source Tailwind CSS file
├── index.html             # Main HTML file
├── README.md              # Project documentation
└── tailwind.config.js     # Tailwind CSS configuration file
```
