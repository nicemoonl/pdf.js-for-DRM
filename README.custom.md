# development

switch to node version 18 by running `nvm use 18`
remove the folder "noed_modules" and run `npm install` 
run `npx http-server` and open `viewer.html` for development and testing

# build project

run `gulp generic` to build project
output files are in `/build/generic/`
copy the contents inside to MMIS

# l10n

for updating l10n for development and testing,
update the file `viewer.properties` in `/l10n/`

# search param

`mob=1` for MOB. fullscreen button will be hidden
`locale=en` for setting UI language. use `tc` and `sc` for Chinese