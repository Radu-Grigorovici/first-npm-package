# @Radu-Grigorovici/first-npm-package

[![GitHub forks](https://img.shields.io/github/forks/Radu-Grigorovici/first-npm-package)](https://github.com/Radu-Grigorovici/first-npm-package/network)
[![GitHub stars](https://img.shields.io/github/stars/Radu-Grigorovici/first-npm-package)](https://github.com/Radu-Grigorovici/first-npm-package/stargazers)
[![GitHub license](https://img.shields.io/github/license/Radu-Grigorovici/first-npm-package)](https://github.com/Radu-Grigorovici/first-npm-package)

First npm package!

Install
\$ npm install @radu.grigorovici/first
Usage
const tiny = require("@radu.grigorovici/first");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
// at tiny (<anonymous>:2:41)
// at <anonymous>:1:1
