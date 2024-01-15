# Learning Tailwind 

### Generate package.json
npm init -y

### Tailwind installation
npm i -D tailwindcss

### Generate tailwind config file
npx tailwind init

### Generate tailwind output file (manual compilation)
npx tailwind -i tailwind.css -o styles.css --minify

### Add vite for automatize tailwind compilation
npm i -D vite postcss autoprefixer
npx tailwindcss init -p

### Execute
npm run dev

### Build to production
npm run build

### Preview build
npm run pewview 
