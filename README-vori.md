To generate dist/ folder

Optionally bump version in lib/package.json

`yarn workspaces run build`

`rm -r -f dist`

`mv lib/build . ; mv build dist`

To publish

`yarn global add gitpkg`

`gitpkg publish`
