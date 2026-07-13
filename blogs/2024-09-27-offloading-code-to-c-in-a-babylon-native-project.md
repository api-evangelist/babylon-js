---
title: "Offloading code to C++ in a Babylon Native project"
url: "https://babylonjs.medium.com/offloading-code-to-c-in-a-babylon-native-project-65b0d1badebc?source=rss-efd98bd3d8f4------2"
date: "2024-09-27"
author: "Babylon.js"
feed_url: "https://babylonjs.medium.com/feed"
---
One benefits of using Babylon Native to run your Babylon.js scripts in a native application is the possibility to have a single codebase across your web and native projects. However, one other major benefit is to be able to offload computationally intensive tasks from the JS to native very seamlessly. This can be a powerful tool in some specific scenarios (such as when JIT is not available), but it might also not bring that many benefits as most people would think.
