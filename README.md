<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/80216211-00ef5280-863e-11ea-81de-59f3a3d4b8e4.png">  
</p>
<p align="center">
    <i></i>
    <br>
    <br>
    <a href="https://github.com/isMattCoding/lunatic-dsfr/actions">
      <img src="https://github.com/isMattCoding/lunatic-dsfr/workflows/ci/badge.svg?branch=main">
    </a>
    <a href="https://bundlephobia.com/package/lunatic-dsfr">
      <img src="https://img.shields.io/bundlephobia/minzip/lunatic-dsfr">
    </a>
    <a href="https://www.npmjs.com/package/lunatic-dsfr">
      <img src="https://img.shields.io/npm/dw/lunatic-dsfr">
    </a>
    <a href="https://github.com/isMattCoding/lunatic-dsfr/blob/main/LICENSE">
      <img src="https://img.shields.io/npm/l/lunatic-dsfr">
    </a>
</p>
<p align="center">
  <a href="https://github.com/isMattCoding/lunatic-dsfr">Home</a>
  -
  <a href="https://github.com/isMattCoding/lunatic-dsfr">Documentation</a>
</p>

# Install / Import

```bash
$ yarn add lunatic-dsfr @codegouvfr/react-dsfr
```

You must follow the setup instruction from [react-dsfr](https://react-dsfr.etalab.studio/).

```typescript
import { MyComponent } from "lunatic-dsfr";
import { MyComponent } from "lunatic-dsfr/MyComponent";
```

# Setup dev environnement

```bash
yarn
```

# Link this module in main project

```bash
cd ~/github
git clone https://github.com/garronej/test-lunatic-dsfr
cd test-lunatic-dsfr
yarn

cd ~/github
git clone https://github.com/isMattCoding/lunatic-dsfr
cd lunatic-dsfr
yarn
yarn build
npx ts-node --skipProject src/scripts/link-in-main-project.ts test-lunatic-dsfr
npx tsc -w

# Open another terminal

cd ~/github/test-lunatic-dsfr
yarn start
```
