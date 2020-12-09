# original tsconfig.app.json file
{
  "extends": "./tsconfig.json",
  "compilerOptions": {
    "outDir": "./out-tsc/app",
    "types": []
  },
  "files": [
    "src/main.ts",
    "src/polyfills.ts"
  ],
  "include": [
    "src/**/*.ts",
    "src/**/*.d.ts"
  ],
  "exclude": [
    "src/**/*.spec.ts"
  ]
}
