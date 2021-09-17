## <p align="center">Ingia</p>

![build](https://travis-ci.com/stefanbc/Ingia.svg?branch=master)

![ingia stefancosma xyz_](https://user-images.githubusercontent.com/1278794/133776699-39ca9689-2483-4a37-afb2-1635f6c60818.png)

A free, single column theme for [Ghost](https://github.com/TryGhost). Originally based on [Kakotopia](https://github.com/ourdarkfuture/kakotopia).

## Instalation

1. Download the theme from GitHub.
2. Upload the theme as described in the [Ghost Documentation](https://docs.ghost.org/concepts/config/).
3. Make sure you replace the URLs in the `partials/social.hbs` file with your own social media URLs.
4. This theme has a custom page named `about`. Checkout the Ghost [docs](https://docs.ghost.org/api/handlebars-themes/context/page/#templates) for more info about custom pages.
5. Additionally you should replace all the image in the `assets/images` folder. You can use [this useful tool](http://realfavicongenerator.net/).

After you've completed the steps above, you can zip the theme and upload it.

**This theme is compatible with Ghost 2.x.**

## Developers

You can install all the theme dependencies using:

```
yarn install
```

Available script you can run for development and production:

* `yarn dev` - will build the whole theme for testing.
* `yarn prod` - will build the whole theme for production.
* `yarn watch` - will watch for any sass file modifications and will build.
* `yarn zip` - will zip the theme for production.
* `yarn validate` - will validate the zip created with the previous command.
* `yarn deploy` - will build the theme for production, zip and validate.
