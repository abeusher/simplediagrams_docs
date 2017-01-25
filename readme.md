SimpleDiagrams Documentation

This repo contains the SimpleDiagrams documentation. 

The complexity in working with these docs is that I use a custom theme. This custom theme is included via pip and stored in the virualenv.

You can see this in the following line in the requirements:

`-e git+https://github.com/danielmcquillen/sphinx_rtd_theme.git#egg=simplediagrams_sphinx_theme`

So, if I make a change to that theme, I have to
1. (be working in simplediagrams4-docs-theme virtualenv)
2. Run `grunt` to compile theme changes
3. Commit changes to github repo
4. Get the dependency updated in this virtual env so that the new styles are captured when doing a `make html`
5. Finally, push docs changes here to git so that ReadTheDocs picks them up. The new styles should go along for the ride.

Looks like doing a 
`pip install -r requirements.txt --ugprade` is does get the theme to update, but somehow `make html` doesn't pick it up.

 