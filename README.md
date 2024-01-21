# 1. About

Blog-Index Universal Website Navigation

![](https://img.shields.io/badge/Base-Vue3-brightgreen.svg)
![](https://img.shields.io/badge/Build-Vite-orange.svg)
![](https://img.shields.io/badge/Installer-Yarn-blue.svg)


This is a universal website navigation page based on Vue. You can use it as a landing page for your personal website, guiding visitors to your blog or other projects. It utilizes responsive layout to ensure compatibility across multiple devices, making it convenient for visitors to explore your personal website. The background image is sourced from Bing's daily pictures.

# 2. Usage

## 2.1 Automatic Deployment

### One-Click Deployment

> This method cannot maintain updates. If you want to keep it updated, please do not use this method and refer to the 'Keep Updated' section below.

Click the button to deploy to Vercel in one click:

[![](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FEsunR%2FBlog-Index&repository-name=Blog-Index)

### Keep Updated

After using the one-click deployment, Vercel will create a new project for you instead of forking this project. This will result in not being able to fetch the project's updates from Github. You can manually fork this project, deploy it using Vercel, and continue to follow the updates of this project.

### Modify Configuration

Go to the Github repository of the project, either created by Vercel or manually forked by yourself. Find the /src/config.ts file and click the 'Edit' button to modify the file content.

Wait for Vercel to redeploy.

## 2.2 Manual Deployment

### Clone the Code and Install Dependencies 

Local environment requirements (can use volta for automatic environment switching):

- node >= 18
- yarn 1.22.19

Clone the code and install dependencies:

```sh
git clone 
cd ./Blog-Index
yarn install
```

### Modify Configuration Files as Needed

Modify the content in the src/config.ts file.


### Build and Compile

```sh
yarn build
```

Deploy the files in the dist directory to your server.

# 3. Development

Local environment requirements (can use volta for automatic environment switching):

- node >= 18
- yarn 1.22.19

Clone the code and install dependencies:

```sh
git clone
cd ./Blog-Index
yarn install
```

Start development mode:

```sh
yarn dev
```

