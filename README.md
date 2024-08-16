The app's live link to test in the browser is:



# FabricMotion Video Editor

Fabric Video Editor is a video editor that runs in the browser. It is built with fabric.js, Next.js (a React framework), Tailwindcss, Mobx, and typescript.


## Samples

### 1. Easy UI
<img width="1727" alt="Screenshot 2024-02-22 at 12 09 30 PM" src="https://github.com/AmitDigga/fabric-video-editor/assets/7884106/7246996c-259c-4730-ba19-af060cc94018">

### 2. The editor supports Animations and Effects

https://github.com/AmitDigga/fabric-video-editor/assets/7884106/61c32181-59c2-427c-b816-c51b40bf8bcc

### 3. Basic Working

https://github.com/AmitDigga/fabric-video-editor/assets/7884106/89674396-a0d3-45a3-b1cd-51097142b8f8



## Tech Stack Overview

This project is a browser-based video editor designed to provide a seamless and interactive editing experience directly in the browser. Below is an overview of the key technologies used in building this application:

1. Fabric.js
Purpose: Fabric.js is a powerful and simple JavaScript canvas library that provides an object model for managing and manipulating vector graphics on the HTML5 canvas. It is used in this project for rendering and interacting with elements such as images, text, and shapes on the video timeline and editor.
2. Next.js (React Framework)
Purpose: Next.js is a popular React framework that enables server-side rendering, static site generation, and efficient routing. It is the backbone of this project, handling the UI, routing, and optimizing the overall performance of the application.
3. Tailwind CSS
Purpose: Tailwind CSS is a utility-first CSS framework that allows for rapid UI development with minimal custom CSS. In this project, it is used for styling components and ensuring a responsive and visually appealing interface.
4. MobX
Purpose: MobX is a state management library that enables the use of observable state and reactive programming. It is used to manage the application state in a predictable and efficient manner, ensuring smooth interactions and updates in the video editor.
5. TypeScript
Purpose: TypeScript is a strongly typed programming language that builds on JavaScript, providing static types. It is used throughout the project to improve code quality, enable better tooling, and reduce runtime errors by catching issues at compile-time.
6. FFmpeg
Purpose: FFmpeg is a versatile multimedia framework that can decode, encode, transcode, and stream audio and video files. In this project, FFmpeg is leveraged through WebAssembly (Wasm) to perform video processing tasks such as cutting, merging, and transcoding videos directly in the browser.
7. Anime.js
Purpose: Anime.js is a lightweight JavaScript animation library that works with CSS properties, SVG, DOM attributes, and JavaScript objects. It is used in this project to create smooth animations for transitions, effects, and interactive elements in the video editor.
How It Works
The video editor runs entirely in the browser, providing a client-side solution without the need for server-side processing. The core of the editor is built using Fabric.js for canvas-based manipulations and FFmpeg for video processing, both of which are integrated within the Next.js framework. Tailwind CSS ensures a modern and responsive UI, while MobX and TypeScript maintain the state and integrity of the application. Anime.js adds dynamic and visually appealing animations, enhancing the user experience.
This combination of technologies creates a robust, interactive, and user-friendly video editor that can handle complex editing tasks directly in the browser.


## Features

- [x] User can add
  - [x] Text
  - [x] Images
  - [x] Video
  - [x] Audio
- [x] User can change
  - [x] Canvas Background Color
- [x] Timeline
- [x] Export Video with Audio
- [x] Animations
- [x] Filters

## Main Issues

1. There might be a problem with audio handling
2. Exported video doesn't have a time duration
3. Exported videos have flickering issue

## Future Features

3. Properties Editing panel
4. Video Trimming

## NextJs Default Guide (Updated)

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

### Getting Started

#### Setup

1. Clone the repo
2. Install the dependencies:
```bash
npm install
```
3. Run the development server:

```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

#### Debugging

1. Run the development server:

```bash
npm run dev
```

2. Then run `Launch Chrome against localhost` in `Run and Debug` tab in VSCode

### Learn More

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

