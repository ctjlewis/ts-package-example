# Pure TypeScript ESM package with Bun

For full runtime and Intellisense types support, you can simply publish the
original source code and configure the package with:

```json
{
  "name": "example",
  "version": "1.0.0",
  "type": "module",
  "module": "index.ts",
  "types": "index.ts"
}
```