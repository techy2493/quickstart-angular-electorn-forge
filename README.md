# Angular Electron Forge

## A Quick-Start App For Angular with Electron using Electron Forge

### Versions

Angular: 16

Electron Forge: 6

### Folder Structure

#### Workspace Root

This is structured as a multi-project angular workspace with the appropriate build files and subfolders you would expect.

#### /projects/electron

This is the main electron application code.

index.ts (also commonly named main.ts) initializes the main application window.

#### /projects/my-app/

This is the mian Angular application and is structured like most other applications

### Making it your own

To start with, replace my-app with the name of your application everywhere it appears.
Do not forget to rename the my-app folder in projects!

Update the package.json with your own information

```
  "name": "angular-electron-forge",
  "productName": "angular-electron-forge",
  "version": "1.0.0",
  "description": "An example project of Angular with Electron Forge",
  "author": {
    "name": "YourName",
    "email": "Your@Email.com"
  },
  "license": "MIT",
```

### Debugging

#### VS Code

Launch with Electron:All configuration.

Electron will appear first and be white, a short while later the angular page will render. Breakpoints in both Main (electorn) and Render (angular) files will be hit.

#### Chrome Dev Tools

Warning, to allow VS Code debugging to bind you must not open the dev tools on load of electron (via main.ts).

Angular Devtools is provided in main.ts
https://angular.io/guide/devtools

### Credits

This project was initially created following a guide by ahmed.loudghiri found at
https://medium.com/@ahmed.loudghiri/bridging-the-gap-crafting-an-angular-electron-application-with-typescript-using-angular-cli-and-74cb359daa4a

### Maintenance

I will update this project every time I update my own projects it is based on however that may be in-frequent. I will be accepting pull requests for anyone interested in contributing.
