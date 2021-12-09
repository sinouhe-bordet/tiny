# @sinouhe_bordet/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@sinouhe_bordet/tiny)](https://github.com/sinouhe-bordet/tiny)
[![npm bundle size](https://img.shields.io/bundlephobia/min/@sinouhe_bordet/tiny)](https://github.com/sinouhe-bordet/tiny)

A tiny boi

##Install
$ npm install @bamblehorse/tiny

##Usage
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1