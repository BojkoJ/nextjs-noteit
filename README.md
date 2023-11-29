<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NoteIt: Your Next-Gen Note-Taking App</title>
  <style>
    body {
      font-family: sans-serif;
    }
    h1, h2, h3 {
      font-weight: bold;
      margin-bottom: 10px;
    }
    ul {
      list-style: none;
      margin-top: 10px;
      padding: 0;
    }
    li {
      margin-bottom: 5px;
    }
    a {
      text-decoration: none;
      color: #007bff;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>NoteIt</h1>
    <h2>Your Next-Gen Note-Taking App</h2>
    <p>NoteIt is a Next.js application that provides a user-friendly platform for taking, organizing, and sharing notes. Inspired by Notion, NoteIt offers a comprehensive set of features to streamline your note-taking experience.</p>
    <h3>Key Features</h3>
    <ul>
      <li>Create and manage notes with ease</li>
      <li>Set note icons and background images</li>
      <li>Utilize structured notes for enhanced organization</li>
      <li>Share notes with others for collaborative work</li>
      <li>Create sub-notes to organize complex information</li>
      <li>Search notes efficiently to find what you need</li>
      <li>Toggle between light and dark mode for personalized viewing</li>
    </ul>
    <h3>Technologies</h3>
    <ul>
      <li>**Next.js 13:** A powerful React framework for building server-side rendered applications</li>
      <li>**Convex Real-time database:** A scalable and reliable database for real-time data synchronization</li>
      <li>**Clerk Authentication:** A secure and user-friendly authentication system</li>
      <li>**TypeScript:** A superset of JavaScript that ensures type safety</li>
      <li>**LucideReact:** A comprehensive icon library for React applications</li>
      <li>**ShadCN UI Components:** A collection of reusable and customizable UI components</li>
      <li>**EdgeStore:** A cloud-based storage solution for image uploading</li>
      <li>**BlockNote text editor:** A versatile text editor for creating structured notes</li>
    </ul>
    <h3>User Experience</h3>
    <p>NoteIt provides a seamless and intuitive user experience, allowing you to effortlessly capture, organize, and share your ideas.</p>
    <h4>Create and Manage Notes</h4>
    <p>Simply click the "New Note" button to start jotting down your thoughts. Edit, organize, and delete notes with ease.</p>
    <h4>Customize Note Appearance</h4>
    <p>Personalize your notes by setting icons and background images that reflect your style or content.</p>
    <h4>Structure Your Notes</h4>
    <p>Utilize the BlockNote text editor to create structured notes with headings, lists, and code blocks.</p>
    <h4>Share Notes</h4>
    <p>Collaborate with others by sharing notes with them. Manage permissions to grant different levels of access.</p>
    <h4>Organize with Sub-notes</h4>
    <p>Create sub-notes (child notes) to organize complex information in a hierarchical structure.</p>
    <h4>Search and Find</h4>
    <p>Easily search through your notes using the powerful search bar.</p>
    <h4>Light and Dark Modes</h4>
    <p>Switch between light and dark mode to suit your preferred viewing experience.</p>
    <h3>Getting Started</h3>
    <p>To get started with NoteIt, follow these steps:</p>
    <ol>
      <li>Clone the repository: <code>git clone <repository_url></code></li>
      <li>Install dependencies: <code>npm install</code></li>
      <li>Create a <code>.env.local</code> file and add your Convex,Clerk and EdgeStore credentials</li>
      <li>Start the development server: <code>npm run dev</code></li>
      <li>Generate convex functions: <code>npx covex dev</code></li>
      </ol>
  </div>
</body>
</html>
