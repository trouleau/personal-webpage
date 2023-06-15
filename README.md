## How to update the website content?

Update whatever content wanted in `/content/`. Use `hugo server` in the root
directory to visualize the changes locally.

## How to deploy the changes to production?

First compile the changes to the public directory by running

```
hugo
```

Then push the changes to the production repo using

```
cd public
git add .
git commit -m "Build website"
git push origin master
```

Verify that the update at <https://trouleau.github.io/>
