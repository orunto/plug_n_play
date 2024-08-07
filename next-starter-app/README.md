# Getting Started
This nextjs (app router) project was boostrapped with `pnpm create next-app`. To get started, install node modules using pnpm. Trust me it's just better that way 😉 

OR 

You can convert it to an npm project before installing like this 👇
- Delete `pnpm-lock.yaml`
- Replace all pnpm calls to npm in `package.json`
- `npm install`


## Pre installed packages
- Styling is done with a combination of SASS and [`Tailwindcss`](https://v2.tailwindcss.com/docs/border-width).

- Animation with the [`Animejs`](https://animejs.com/documentation/) and the [`AOS Library`](https://github.com/michalsnik/aos/) for simple scroll transitions

## Structure
```
├───app
├───components
│   ├───atoms
│   ├───molecules
│   └───compounds
├───fonts
└───public
```

- Atom components are single function uncomplicated components like buttons 
- Molecules are more complex and contain two or more atom components e.g Navbars
- Compounds contain multiple molecule and atom components e.g Modal popup forms