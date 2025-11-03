# 1) Scaffold
npm create vite@latest . -- --template react-ts
npm i
npm i -D tailwindcss postcss autoprefixer @types/node gh-pages
npx tailwindcss init -p

# 2) shadcn/ui + deps
npm i class-variance-authority clsx tailwind-merge tailwindcss-animate @radix-ui/react-slot
npx shadcn@latest init
npx shadcn@latest add button card input label
