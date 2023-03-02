# NextJS-NodeJS14.x-Template

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app --typescript`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app). With .lyrid-definition.yml packaged together as a default template.

### Lyrid now supports NextJS12 natively.
With our newest update, user no longer need to pack NextJS into ExpressJS. Just copy the `.lyrid-definition.yml` file to
project root and configure the file according to your liking.
```bash
name: <Application Name>
description: <Application Description>
ignoreFiles: .git .next node_modules
modules:
  - name: <Module Name>
    language: nodejs14.x
    web: nextjs
    description: <Module Description>
    functions:
      - name: <Function Name>
        entry: entry.js
        description: the entry point for the function
```

### Deploying on Lyrid
Start uploading the project using [lc code submit !](https://docs.lyrid.io/installation)

<a href="https://app.lyrid.io/login?one-click-deploy=true&origin=github&repository-url=https://github.com/LyridInc/NextJS.TypeScript-Node14.x-Template.git&env=empty&project-type=nextjs&repo-name=NextJS.TypeScript-Node14.x-Template">
  <button>
    <img src="/public/svg/ocd_deploy_to_lyrid.svg" style="height: 50px; width:200px;"/>
  </button>
</a>


