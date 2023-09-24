# Varbase Storybook

This is a placeholder folder to build the static storybook on builds.

> This will show up when the setup fails to build or point in the right way.
> or when the auto storybook build system fails with a bug in components.

To build the static Storybook:
Follow with [Integration of Varbase with Storybook](https://docs.varbase.vardot.com/v/10.0.x/developers/theme-development-with-varbase/integration-of-varbase-with-storybook)
Make sure that the site is configured.

```
yarn install
yarn storybook:build
```

> From this point onward, you can easily access the static storybook,
> by going to `"http://PROJECT_DOMAIN/storybook"`.

> Use the `varbase:http` upstream route, which applies when the main domain, like `"https://main-xxxxxxx-xxxxxxxxxxxx.us.platformsh.site"`,
> is set up to point to the `"PROJECT_FOLDER/docroot"` directory.

> Use the `storybook:http` upstream route, which configured with a subdomain, like `"storybook.main-xxxxxxx-xxxxxxxxxxxx.us.platformsh.site"`,
> it will instead point to the `"PROJECT_FOLDER/storybook"` directory.

> By the way the `applications.yaml` and `routes.yaml` in
> the `.platform` have all configs ready for the **Varbase Platform.sh Template**.
