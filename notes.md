## Serve slides as html
Here's how to serve your slides to a local https server (the code cells will be non-executable):

```
jupyter-nbconvert --to slides presentation.ipynb --post serve
```

## Download the slides as html and host on GitHub pages
From the jupyter notebook interface, click 'File' > 'Download As' > 'slides (.slides.html)'.

If you want to set up github pages to automatically point to this html file:

1. Create a `docs/` directory in your repository,
2. Rename the file from `presentation.slides.html` to `inde.html`
3. Put `index.html` inside the `docs/` folder and commit it to git
4. In the settings of your repository, enable github pages from `docs/`
