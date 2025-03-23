# Counter-Web-App
1. Create a New Vite + React App
   **paste all npm command in terminal 
   npm create vite@latest instagram-auth --template react
    cd instagram-auth
   npm install 
2.Install Tailwind CSS
   npm install tailwindcss @tailwindcss/vite
  **Add the @tailwindcss/vite plugin to your Vite configuration.
   in vite.cofig.js

   import tailwindcss from '@tailwindcss/vite'
   plugins: [
    tailwindcss(),
   ],

3. Add Tailwind Directives
   In src/index.css, replace all content with:
  @import "tailwindcss";

4.clear all the code of app.css index.css

5.add IncDec.jsx 
  ./src/component/IncDec.jsx 
 
replace code of app.jsx from 
  import LogSign from './components/IncDec';

  export default function App() {
  return (
    <IncDec/>
  );
 }

5. Start the Dev Server
   npm run dev
