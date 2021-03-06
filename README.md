<a href="https://fermiumlabs.com/">
    <img src="https://fermiumlabs.com/wp-content/uploads/2019/02/Horizontal-Main_500px.png" alt="Fermium LABS logo" width="200" align="right" />
</a>

# Data-chan NodeJS API

[![npm](https://img.shields.io/npm/v/data-chan.svg)](https://www.npmjs.com/package/data-chan) [![npm](https://img.shields.io/npm/l/data-chan.svg)]() [![npm](https://img.shields.io/npm/dm/data-chan.svg)](https://www.npmjs.com/package/data-chan)


[![wercker status](https://app.wercker.com/status/a7a63b97b9860b3125b0c213b1b468f4/s/master "wercker status")](https://app.wercker.com/project/byKey/a7a63b97b9860b3125b0c213b1b468f4) *Software release* 

[![Build Status](https://drone-ci.dev.fermiumlabs.com/api/badges/fermiumlabs/data-chan-nodejs/status.svg)](https://drone-ci.dev.fermiumlabs.com/fermiumlabs/data-chan-nodejs) *Hardware testing*

This library implements NodeJS APIs for [Data-chan](https://github.com/neroreflex/data-chan)

It uses [foreign function interface](https://github.com/node-ffi/node-ffi) to do so, and is compatible with both NodeJS and [Electron](https://electron.atom.io/) applications

To install:

```shell
npm install data-chan
```

To test, run:

```shell
git clone git@github.com:fermiumlabs/data-chan-nodejs.git
npm install
npm rebuild
npm run test
```

To publish, run:

```shell
npm version patch/minor/major
git push
# and stop here, no npm publish, the CI will take care of that!
```

---


<a href="https://twitter.com/intent/user?screen_name=fermiumlabs">
    <img src="https://img.shields.io/twitter/follow/fermiumlabs.svg?style=social&label=Follow" alt="Follow Fermium LABS on Twitter" align="right" />
</a>
