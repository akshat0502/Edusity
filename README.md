<h1>
  <a href="https://edusity-six-beige.vercel.app/">
    <span>Edusity <hr></span>
  </a>
</h1>
<ul>
  <li><p><b>Edusity</b> is a React.js-based web application designed to showcase college programs, campus life, and resources in an engaging and accessible manner. Its intuitive, responsive design ensures a seamless user experience across all devices.</p></li>
  <li><p>Prospective students can explore detailed information about academic programs, admission requirements, and extracurricular activities. The platform features virtual campus tours, photo galleries, and testimonials to provide an immersive look into college life.</p></li>
  <li><p>Current students can access campus news, event calendars, and student services, creating a centralized hub for information.</p></li>
  <li><p>For administrators, <b>Edusity</b> offers tools to update program details, manage events, and communicate with students effectively, fostering an interactive campus community.</p></li>
</ul>

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
<h1>College Landing Page Using React</h1>
<p>This guide explains how to create and run a React-based frontend for a College Landing Page.</p>
<h2>Steps to Run the React App:</h2>
<ol>
  <li>
    <b>Install Node.js:</b>
    <p>Ensure you have Node.js installed on your system. Download it from <a href="https://nodejs.org" target="_blank">https://nodejs.org</a>.</p>
  </li>
  <li>
    <b>Set Up a React Project:</b>
    <p>Use <code>create-react-app</code> to set up your React project:</p>
    <pre><code>npx create-react-app college-landing-page</code></pre>
  </li>
  <li>
    <b>Navigate to the Project Directory:</b>
    <pre><code>cd college-landing-page</code></pre>
  </li>
  <li>
    <b>Build the College Landing Page:</b>
    <p>Customize the app by editing files in the <code>src</code> folder. You can create components for:</p>
    <ul>
      <li>Homepage with an introduction to the college</li>
      <li>About section with details of the institution</li>
      <li>Programs offered</li>
      <li>Admissions and contact forms</li>
    </ul>
  </li>
  <li>
    <b>Build for Production:</b>
    <p>When your app is ready for deployment, run:</p>
    <pre><code>npm run build</code></pre>
    <p>This creates an optimized production build in the <code>build</code> folder.</p>
  </li>
</ol>

<h2>Folder Structure:</h2>
<pre><code>
  college-landing-page/
  ├── public/       // Static files (e.g., index.html)
  ├── src/          // React components, styles, and logic
  │   ├── components/  // Reusable UI components
  │   ├── pages/        // Pages like Home, About, Programs, Admissions
  │   ├── App.js        // Main app component
  │   ├── index.js      // Entry point
  ├── package.json  // Project dependencies and scripts
</code></pre>
<h2>Tips:</h2>
<ul>
  <li>Use a component library like <a href="https://mui.com/" target="_blank">Material-UI</a> or <a href="https://ant.design/" target="_blank">Ant Design</a> for pre-designed UI components.</li>
  <li>Add animations and transitions to enhance user experience (e.g., using <a href="https://reactcommunity.org/react-transition-group/" target="_blank">React Transition Group</a>).</li>
  <li>Ensure the website is responsive and optimized for different devices.</li>
</ul>
