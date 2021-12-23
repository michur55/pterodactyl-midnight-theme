Put the resources folder in /var/www/pterodactyl

After you do that, build the panel. https://pterodactyl.io/community/customization/panel.html

Instead of doing "Yarn build:production" do this, "rm -r .babel-plugin-macrosrc.js && yarn add @emotion/react && yarn build:production"

If you want to remove the theme just follow the upgrading guide on pterodactyl's website.

If you want to change colors edit stylesheet.css in /resources/scripts/stylesheet.css

There will be variables at the top of the file, change them accordingly, and then build the panel.