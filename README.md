# Build an app (macOS)

Navigate to one of the app directories and run the following commands:

```bash
npm install --save-dev electron

npm install -g electron-packager

electron-packager . Google\ Drive platform=darwin --icon=icons/icon --overwrite
```

A new directory will be created inside the app directory that contains the built app.
