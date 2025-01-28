# testing lightbox2 dependencies

```
npm i 
npm run dev
```

to test the build
```
npm run build
npm run preview
```
the files are rendered from `/dist` folder,
there're no references to `node_modules`, ie. you can "safely" delete it

it seems that a correct build process, can avoid references to resources in `node_modules`...
