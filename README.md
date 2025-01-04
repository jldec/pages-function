# pages-function
https://developers.cloudflare.com/pages/functions/get-started/

```sh
pnpm install
pnpm dev # runs `wrangler pages dev site`
pnpm ship # runs `wranger pages deploy site`
```

> [!TIP]
> Drag and drop deployments made from the Cloudflare dashboard do not currently support compiling a functions folder of Pages Functions. To deploy a functions folder, you must use Wrangler. When deploying a project using Wrangler, if a functions folder exists where the command is run, that functions folder will be uploaded with the project.
> https://developers.cloudflare.com/pages/get-started/direct-upload/#functions

