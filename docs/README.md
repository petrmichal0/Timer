# Timer

## Project Title and Description
Timer is a web application designed to help users set, manage, and track multiple timers. Users can add new timers, edit existing ones, and keep track of their remaining time.

## Badges
![Static Badge](https://img.shields.io/badge/status-online-brightgreen)

## Quick Look
<img src="https://github.com/user-attachments/assets/6f17781e-a2f2-424f-b6d5-1c3af8d02f28" width="700" alt="Timer App Demo">

## Table of Content
- [Project Title and Description](#project-title-and-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Demo (link)](#demo-link)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Third-Party Libraries](#third-party-libraries)
- [License](#license)

## Features
- Create and manage multiple timers
- Edit existing timers
- Track remaining time
- User-friendly interface

## Installation

### Prerequisites
- Node.js (v12 or higher)
- npm (v6 or higher)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/petrmichal0/Timer.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Timer
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

## Usage
To start the application, run the following command:
```bash
npm run dev
```

After starting, go to [http://localhost:3000](http://localhost:3000) in your web browser.

## Screenshots

<table>
  <tr>
    <th>Homepage</th>
    <th>Timer Management</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/37080a48-02ca-44b5-a3fa-9fc61e86d386" width="300" height="300" alt="Homepage">
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/be7de6eb-b3e8-4d31-a328-d9329ca807c8" width="300" height="300" alt="Timer Management">
    </td>
  </tr>
</table>

## Demo (link)

Check out the live demo of the application [here](https://react-timers.netlify.app/).

## Project Structure

```css
Timer/
├── public/
│   ├── vite.svg
├── src/
│   ├── components/
│   │   ├── UI/
│   │   │   ├── AddTimer.tsx
│   │   ├── Header.tsx
│   │   ├── Timer.tsx
│   │   ├── Timers.tsx
│   ├── store/
│   │   ├── timers-context.tsx
│   ├── App.tsx
│   ├── index.css
│   ├── main.tsx
│   ├── vite-env.d.ts
├── .eslintrc.cjs
├── .gitignore
├── README.md
├── index.html
├── package-lock.json
├── package.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## Technologies Used

[![React Badge](https://img.shields.io/badge/-React-61DBFB?style=for-the-badge&labelColor=black&logo=react&logoColor=61DBFB)](#)
[![TypeScript Badge](https://img.shields.io/badge/-TypeScript-007ACC?style=for-the-badge&labelColor=black&logo=typescript&logoColor=007ACC)](#)
[![Vite Badge](https://img.shields.io/badge/-Vite-646CFF?style=for-the-badge&labelColor=black&logo=vite&logoColor=646CFF)](#)

## Third-Party Libraries

* React Router

## License

This project is licensed under the MIT License - see the LICENSE file for details.
