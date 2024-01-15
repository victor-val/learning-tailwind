
## Generate package.json
npm init -y

## Tailwind installation
npm i -D tailwindcss

## Generate tailwind config file
npx tailwind init

## Generate tailwind output file (manual compilation)
npx tailwind -i tailwind.css -o styles.css --minify