### This is the default addon repository for [Stremio Addon Manager](https://github.com/rleroi/stremio-addon-manager).

TO submit an addon, please create an [Issue](https://github.com/rleroi/stremio-addon-manager-repository/issues/new) with with the following content:
```json
{
  "name": "Your addon name (must be unique)",
  "description": "Some description for your adon",
  "logo": "icon URL",
  "url": "The git repository URL",
  "install": "the command to run after pulling your repo to install the addon. E.g. npm install",
  "start": "the command to start your addon. E.g. npm run start"
}
```
