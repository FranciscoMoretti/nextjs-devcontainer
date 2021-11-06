# A Next.js template to setup a VS Code devcontainer
A simple and minimalistic template to develop Next.js code in a VS Code development container.

## Features
- Node + Typescript
- Git
- Fast Refresh


## Pre-requisites
1. [Set up git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) in your host machine or follow with a credentials manager.

## Steps
1. Build and Activate the [Development Container](https://code.visualstudio.com/docs/remote/containers).
   1. Follow the VS Code containers [Getting Started Guide](https://code.visualstudio.com/docs/remote/containers#_getting-started).
   2. Open the repository folder in a container by following [these steps](https://code.visualstudio.com/docs/remote/containers#_quick-start-open-an-existing-folder-in-a-container).
2. Setup your Next.js application by using one of these two options
   - **Option 1:** Follow the tutorial to [Create a Next.js App](https://nextjs.org/learn/basics/create-nextjs-app)
      ```bash
      npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/learn-starter"
      ```
   - **Option 2:** Add your Next.js project as a [Git Submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
      ```
      git submodule add https://github.com/cassidoo/next-netlify-starter.git
      ```

3. Go to the newly created directory to run `npm` commands. In this case it should be:
   ```bash
   cd `your_project_folder`
   ```
4. Run the development server
   ```bash
   npm run dev
   ```