# Vite Azure Static Web App + Functions Template
This template should help get you started developing with [`Svelte`](https://github.com/sveltejs/svelte) 
and [`TypeScript`](https://github.com/microsoft/TypeScript) 
in [`Vite`](https://github.com/vitejs/vite)
using [*Azure Static Web Apps*](https://azure.microsoft.com/en-us/services/app-service/static) + [*Serverless Functions*](https://azure.microsoft.com/en-us/services/functions/).

# Notice
This template may require a different version of node to the one that is already installed, to find your current version by running 

```
C:\>node --version
v14.19.0
```

You can find the supported versions on Microsoft's [Developer Reference](https://aka.ms/functions-node-versions)

# Update Azure Functions Core
You may need to update Microsoft's [`azure-functions-core-tools`](https://github.com/Azure/azure-functions-core-tools) globally to v4 (latest at the commit date, supports node v14 and preview support for v16)

```bash
npm i -g azure-functions-core-tools@4 --unsafe-perm true
```

# Usage
Run `npm install` or `yarn` to install the dependencies

## Building
```
yarn build
```

## Development
This command will use [`concurrently`](https://github.com/open-cli-tools/concurrently) to run the frontend development server, backend compile task, and Azure emulator
```
yarn dev:local
```



