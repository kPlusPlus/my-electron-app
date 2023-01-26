https://www.electronjs.org/docs/latest/tutorial/quick-start

mkdir my-electron-app && cd my-electron-app
npm init

npm install --save-dev electron



https://www.electronforge.io/import-existing-project
npm install --save-dev @electron-forge/cli
npm exec --package=@electron-forge/cli -c "electron-forge import"
npm install --save-dev @electron-forge/cli @electron-forge/maker-squirrel @electron-forge/maker-deb @electron-forge/maker-zip


npm install --global windows-build-tools


An unhandled rejection has occurred inside Forge:
Error: Could not find any make targets configured for the "win32" platform.
at Task.task (D:\my-electron-app\node_modules\@electron-forge\core\dist\api\make.js:122:27)
    at Task.run (D:\my-electron-app\node_modules\listr2\dist\index.cjs:978:35)
