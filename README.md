# SVGGenie

**SVGGenie** is a powerful tool designed to generate scalable SVG graphics from text inputs using AI. It simplifies the process of creating animations and vector graphics, making them accessible to both developers and designers without requiring in-depth knowledge of vector design or coding.

## Purpose

The primary goal of SVGGenie is to help developers and designers:

- Automate the creation of SVG graphics and animations.
- Save time on manual SVG coding by providing AI-powered automation.
- Enhance user interfaces with dynamic, visually appealing SVGs.

## Features

- **AI-Powered SVG Generation**: Uses Google Gemini Generative AI for transforming text prompts into vector graphics.
- **Dynamic Preview**: React-powered UI with real-time updates.
- **Firebase Integration**: For secure data storage and user management.
- **Customizable Outputs**: Modify and download generated SVG files.
- **Modern UI**: Styled with Tailwind CSS for responsiveness and simplicity.

## How SVG Animations Help Developers

SVG animations offer numerous benefits, making them a vital part of modern web development:

1. **Enhance Visual Appeal**  
   Animated SVGs add dynamic and interactive elements to websites, capturing user attention and enhancing overall aesthetics.

2. **Scalability**  
   SVGs maintain their quality regardless of screen size or resolution, making them ideal for responsive and high-DPI designs.

3. **Performance Optimization**  
   Lightweight and fast-loading, SVG animations are more efficient compared to GIFs, images, or videos.

4. **Interactive**  
   SVGs can be animated using CSS, JavaScript, or libraries like GSAP, providing precise control over transitions and interactions.

5. **Reusable and Modular**  
   Developers can easily reuse animated SVG components across multiple projects, ensuring consistency and reducing redundant efforts.

By automating SVG generation, **SVGGenie** empowers developers to utilize these benefits seamlessly, improving workflows and enabling the integration of engaging visuals into their applications.

## Get Started

1. Input descriptive text to generate your SVG graphic.
2. Preview the real-time result.
3. Customize and download your scalable, animated SVG for use in your projects.

**Leverage the power of SVG animations to transform your designs with SVGGenie!**

## Getting Started

Follow these steps to set up and run the project locally:

## Environment Variables

To run the project, you need to configure the following environment variables in a `.env` file:

1. **VITE_GEMINI_API**  
   API key for the Google Gemini Generative AI service.

2. **VITE_FIREBASE_API**  
   Firebase API key for authentication and backend services.

3. **VITE_FIREBASE_DB_URL**  
   Firebase Realtime Database URL for storing and retrieving data.

### 1. Clone the Repository

```bash
git clone https://github.com/Fuzailkazi/SVGGenie.git
```

### 2. Change your directory

```bash
cd text2svg
```

### 3. Install all the dependencies

```bash
npm install
```

### 4. Run the project

```bash
npm run dev
```
