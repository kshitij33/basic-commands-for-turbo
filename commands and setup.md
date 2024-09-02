
# Project Setup and Basic Commands



## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- **Node.js**: Version 14 or higher
- **npm**: Version 6 or higher (comes with Node.js)

You can check if you have Node.js and npm installed by running:

```bash
node -v
npm -v
```

## Installation
-- Install pnpm globally 
```
	npm install -g pnpm
```
-- Install Turbo Repo
```
npm install -g turbo
```
##  Setup the Project
Once you have cloned the project make sure to run the following command in the root directory to install all the dependencies into the apps.
```
pnpm install
```

## Running the Project
To run the project run the following command
```
pnpm run dev
```

## Installing dependencies in a particular Directory
Sometimes there may be a case where you want to install a directory to a particular app. The command for that is 
```
npm install package_name --workspace=app1 --workspace=app2 --save-dev
```

## ESlint
```
pnpm run lint
```

## Code Formating (Prettier)
```
pnpm run format
```


