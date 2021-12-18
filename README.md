# angular_upgrade_tips
tips for upgrading the angular in local project


ng update -- to update angular for the local project

open package.json to change all the angular items in "dependencies" and "devDependencies" from 12 to 13
ex:





"dependencies": {


"@angular/animations": "~13.1.1",
"@angular/cdk": "^13.1.1",
"@angular/common": "~13.1.1",
"@angular/compiler": "~13.1.1",
"@angular/core": "~13.1.1",
"@angular/forms": "~13.1.1",
"@angular/material": "^13.1.1",
"@angular/platform-browser": "~13.1.1",
"@angular/platform-browser-dynamic": "~13.1.1",
"@angular/router": "~13.1.1",


}





"devDependencies": {

"@angular-devkit/build-angular": "~13.1.1",
"@angular/cli": "~13.1.1",
"@angular/compiler-cli": "~13.1.1",
"typescript": "~4.5.4"

}

npm install

All done
