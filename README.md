# ZeroToProductionTailwind

PS C:\TheGym\ZeroToProductionTailwind> live-server
Serving "C:\TheGym\ZeroToProductionTailwind" at http://127.0.0.1:8080
Ready for changes
GET /favicon.ico 404 7.302 ms - 150
Change detected C:\TheGym\ZeroToProductionTailwind\css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
CSS change detected C:\TheGym\ZeroToProductionTailwind\css\tailwind.css
PS C:\TheGym\ZeroToProductionTailwind> npx tailwind-cli build css/tailwind.css -o build/tailwind.css
npm error 404 Not Found - GET https://registry.npmjs.org/tailwind-cli - Not found
npm error 404  'tailwind-cli@*' is not in this registry.
npm error 404
npm error 404 Note that you can also install from a
npm error 404 tarball, folder, http url, or git url.
npm error A complete log of this run can be found in: C:\Users\UMWIZERWA\AppData\Local\npm-cache\_logs\2025-03-17T09_27_11_299Z-debug-0.log
PS C:\TheGym\ZeroToProductionTailwind> npx tailwindcss-cli build css/tailwind.css -o build/tailwind.css
[deprecation] Running tailwindcss without -i, please provide an input file.
PS C:\TheGym\ZeroToProductionTailwind> npx tailwindcss-cli build css/tailwind.css -o build/tailwind.css -i
C:\Users\UMWIZERWA\AppData\Local\npm-cache\_npx\8bcfa250e55e6bf5\node_modules\tailwindcss\lib\cli.js:317
    throw err;
    ^

ArgError: option requires argument: -i (alias for --input)
    at arg (C:\Users\UMWIZERWA\AppData\Local\npm-cache\_npx\8bcfa250e55e6bf5\node_modules\arg\index.js:164:13)
    at C:\Users\UMWIZERWA\AppData\Local\npm-cache\_npx\8bcfa250e55e6bf5\node_modules\tailwindcss\lib\cli.js:261:35      
    at Object.<anonymous> (C:\Users\UMWIZERWA\AppData\Local\npm-cache\_npx\8bcfa250e55e6bf5\node_modules\tailwindcss\lib\cli.js:319:3)
    at Module._compile (node:internal/modules/cjs/loader:1546:14)
    at Object..js (node:internal/modules/cjs/loader:1689:10)
    at Function._load (node:internal/modules/cjs/loader:1128:12)
    at TracingChannel.traceSync (node:diagnostics_channel:315:14)
PS C:\TheGym\ZeroToProductionTailwind> npm init -y
Wrote to C:\TheGym\ZeroToProductionTailwind\package.json:

{
  "name": "zerotoproductiontailwind",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/Umwizer/ZeroToProductionTailwind.git"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/Umwizer/ZeroToProductionTailwind/issues"
  },
  "homepage": "https://github.com/Umwizer/ZeroToProductionTailwind#readme"
}



PS C:\TheGym\ZeroToProductionTailwind> npm install -D tailwindcss postcss autoprefexer vite
npm error 404 Not Found - GET https://registry.npmjs.org/autoprefexer - Not found
npm error 404
npm error 404  'autoprefexer@*' is not in this registry.
npm error 404
npm error 404 Note that you can also install from a
npm error 404 tarball, folder, http url, or git url.
npm error A complete log of this run can be found in: C:\Users\UMWIZERWA\AppData\Local\npm-cache\_logs\2025-03-17T09_45_37_937Z-debug-0.log
PS C:\TheGym\ZeroToProductionTailwind> npm install -D tailwindcss postcss autoprefixer vite

added 21 packages, and audited 22 packages in 19s

8 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
PS C:\TheGym\ZeroToProductionTailwind> npx tailwindcss init -p