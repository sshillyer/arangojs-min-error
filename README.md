# arangojs-min-error
Example of how to reproduce an error when trying to use arangojs module
##
To reproduce, ```git clone``` the project then run:
```
npm i
npm run build
```

## Errors
Error 1:
```
node_modules/arangojs/lib/cjs/collection.d.ts:91:27 - error TS2304: Cannot find name 'Blob'.

91     import(data: Buffer | Blob | string | any[], { type, ...opts }?: ImportOptions): Promise<ImportResult>;
```
Error 2:
```
node_modules/arangojs/lib/cjs/database.d.ts:125:54 - error TS2304: Cannot find name 'Blob'.

125     downloadService(mount: string): Promise<Buffer | Blob>;
```
