# ad-oneframework
Repo for ADThemes One Framework Files

These are specific to ADThemes and Sites. 

# Setup
Site Specific CSS goes in the _site-layout.scss partial

Use the @import rule to import the dirrent partials you would like to use from the framework in the layout.scss file located in webroot, the framework uses fontawesome in some of the navigational elements so be sure to include it with the @import rule

Most work will be done in the _variables.scss partial, colors, fonts, etc and can be added to accordingly.

# The JS
The two JS files included handle both the dropdown menu and the responsive menu, make sure to add both to your assets.json file 
