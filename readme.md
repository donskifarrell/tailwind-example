## Tailwind Example

Basic showcase of the output from using TailwindCSS with PostCSS.

I've included the generated output in `./dist` folder so you can directly see what's generated. Load `./dist/index.html` in your browser for a preview.

If you want, delete the `./dist/app.cleancss.css` file and run:

```
yarn install
yarn build
```

This will run the same command as in the `assetgen` pipeline, using tailwindcss and autoprefixer. Additionally, it will run the CSS through PurgeCSS and Clean-css, using very basic optimisation settings.

## Outputs:

Here are expected sizes for the various build stages.
Obviously this is a very simple example and we would expect the sizes to grow as we add to templates.

Unoptimised css -> `~1.7 MB`

with PurgeCSS -> `~8 KB`

with PurgeCSS & Cleancss -> `633 B`
