# Plug'n Play
This project is a compilation of starter templates and component libraries for various frontend web development frameworks.

## What we have here
Currently the project only has a [`Next.js starter`](/next-starter/) filled with useful components I've built over the past year of using the framework that I've had to copy and paste across several projects. These components range from simple buttons to complex app features complete with their own micro-interactive animations.

## Getting started
You'll need the latest LTS version of NodeJs to get started.

### <u>If you want all the templates</u>
First clone the repository
```bash
git clone git@github.com:orunto/plug_n_play.git

# After cloning is complete navigate to your preferred starter
cd preffered-starter

npm install
```

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```
<br/>

### <u>Or you just want a specific starter</u>
#### Next.js
```bash
npx create-next-app [project-name] -e https://github.com/orunto/plug_n_play/next-starter
```