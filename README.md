# Clasp Typescript Template

Environment for Google App Script with Typescript, ESLint, Prettier and other npm packages

## Usage

### Clasp

**.clasp.json.dev**

add your scriptId

- **Dev Environment:** `.clasp.json.dev`
- **Prod Environment:** `.clasp.json.prod`

```
{"scriptId":" YOUR SCRIPT ID "}
```

**appscript.json**

change appscript.json you want

- Time Zone（default: "Asia/Tokyo"）
- OAuth

### npm

install packages

```
npm install
```

linter

```
npm run lint
```

deploy

```
npm run deploy:dev
npm run deploy:prod
```
