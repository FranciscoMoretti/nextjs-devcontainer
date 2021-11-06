# A Next.js template to setup a VS Code devcontainer


## Steps
1. Enter the devcontainer
2. Follow the tutorial to [Create a Next.js App](https://nextjs.org/learn/basics/create-nextjs-app) but point to the root directory
   ```bash
   npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/learn-starter"
   ```
3. Go to the newly created directory to run `npm` commands. In this case it should be:
   ```bash
   cd nextjs-blog
   ```
4. Run the development server
   ```
   npm run dev
   ```