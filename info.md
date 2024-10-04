`command to install tailwind css in your html code : `

`1` __npm install -D tailwindcss__
`2` __npx tailwindcss init__
`3` **npx tailwindcss -i ./style.css -o `./src/output.css` --watch** ||
`3` **npx tailwindcss -i ./style.css -o `./output.css` --watch**


**tailwind config.js**
`/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["*"],
  theme: {
    extend: {
      fontFamily:{
        'display':['Poppins','sans-serif'],
        'body':['Inter','sans-serif']
      }

    },

  },
  plugins: [],
}

`

**style.css**
`@tailwind base;
@tailwind components;
@tailwind utilities;
`