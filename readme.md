# Simple Tailwind Starter

This is a simple Tailwind starter project using the Tailwind CLI. It is meant to be used as a starting point for your projects. This is the same setup used in my [Tailwind From Scratch Course](https://www.traversymedia.com/tailwind-css-course).

## Usage

Clone the repo:

```bash
git clone
```

Install the dependencies:

```bash
npm install
```

Build or watch the CSS file:

```bash
# Build once
npm run build

# Watch for changes
npm run watch
```


# DEMO

```
npm init -y

cat package.json

# For development
npm -i -D tailwindcss

# For Production
npm -i tailwindcss

npx tailwindcss init
vi tailwind.config.js
content: ['./*.html']

touch input.css
vi input.css
@tailwind base;
@tailwind components;
@tailwind utilities;

vi package.json
"scripts": {
  "build": "tailwindcss -i ./input.css -o ./css/style.css",
  "watch": "tailwindcss -i ./input.css -o ./css/style.css --watch"
  
}



npm run build


vi index.html
! enter

```

This will watch the `src/input.css` file and build it to `css/style.css`, which will be your final CSS file.

## License

This project is open source and available under the [MIT License](LICENSE).
