## Tailwind Example

Basic showcase of the output from using TailwindCSS with PostCSS.

I've included the generated output in `./dist` folder so you can directly see what's generated. Load `./dist/index.html` in your browser for a preview.

If you want, delete the `./dist/app.postcss.css` file and run:

```
yarn install
yarn build
```

This will run the same command as in the `assetgen` pipeline, using tailwindcss and autoprefixer

## Note:

The generated css file is _massive_. It is expected to be run through cleancss, purgecss or similar to remove unused css.
