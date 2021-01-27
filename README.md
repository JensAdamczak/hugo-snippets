# Example site 

The branch example-site contains a working example on how to create a website using the [Snippets
Hugo theme](https://github.com/JensAdamczak/hugo-snippets).

It uses the theme as a submodule. In case the code of the theme has changed, the submodule can be
updated with 

```
git submodule update --remote --recursive
git commit -a -m 'Update submodule'
git push origin example-site
```

The site can be rebuild after the change with

```
bash publish.sh
cd public
git push --all
cd ..
```

