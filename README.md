# wtf-homepage

wtf homepage project

## Deploy

To deploy public folder to **gh-pages** brunch

> git checkout gh-pages
> git checkout [master/feature-branch] -- 'public/**'
> git mv -f public/** ./
> git rm -f -r public/**
> git commit . -m "feat: fresh website deploy `date +\"%Y-%m-%d\"`"
