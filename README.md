# Nextjs-Architecture
Standard scalable boilerplate for Nextjs projects

![Design](https://github.com/pranansh-s/nextjs-architecture/assets/43909197/48417749-f6e0-47f2-9055-bed8790cb408)

## **Contains**
* NextJS
* ReactJS
* TailwindCSS
* esLint
* Prettier
* PostCSS
* Autoprefixer

Works great with large scale projects with multiple contributors </br>
made for personal use but you are always welcome to use it 🫡😇🤧🤧
</br></br>
</br></br>
</br></br>
</br></br>
note: If you wish to use a Typescript version make sure to run these commands to install Typescript and typings for React </br>
```CLI
npm install --save-dev typescript
npm install --save-dev @types/react @types/react-dom
```
Rename all the file extensions from .js to .ts or .jsx to .tsx
and add the following code in `tsconfig.json` at root directory

```JSON
{
  "compilerOptions": {
    "target": "esnext",
    "module": "commonjs",
    "jsx": "preserve",
    "lib": ["dom", "dom.iterable", "esnext"],
    "allowJs": true,
    "esModuleInterop": true,
    "skipLibCheck": true,
    "strict": false,
    "forceConsistentCasingInFileNames": true,
    "noEmit": true,
    "resolveJsonModule": true,
    "isolatedModules": true,
    "incremental": true
  },
  "include": ["next-env.d.ts", "**/*.ts", "**/*.tsx"],
  "exclude": ["node_modules"]
}
```
