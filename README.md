### tailwind-project-1



### commands:

npm init -y

npm i -D tailwindcss

npx tailwindcss init

touch input.css

"scripts": {
    "build": "tailwindcss -i ./input.css -o ./css/main.css",
    "watch": "tailwindcss -i ./input.css -o ./css/main.css --watch"
  },