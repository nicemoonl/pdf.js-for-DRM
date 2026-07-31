# development

remove the folder "noed_modules" and run `npm install` 
run `npx http-server` and open `viewer.html` for development and testing

# build project

run `npx gulp generic` to build project
output files are in `/build/generic/`
copy the contents inside to MMIS

# l10n

for updating l10n for development and testing,
update the file `viewer.ftl` in `/l10n/`
and then run `npx gulp locale`

# search param

`mob=1` for MOB. fullscreen button will be hidden
`locale=en` for setting UI language. use `tc` and `sc` for Chinese