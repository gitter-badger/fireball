Fireball is a next-gen Html5 game editor built with extremely extendable structure. 

Fireball is currently using [Pixi.js](https://github.com/GoodBoyDigital/pixi.js/) and [Cocos2D-JS](https://github.com/cocos2d/cocos2d-html5) as game engine. We will be supporting more open sourced game engines in the future.

![Fireball Game Engine](https://cloud.githubusercontent.com/assets/344547/6882303/a8b7a740-d5ba-11e4-9518-e6494b1c94fa.png)

## Introduction

The core of Fireball is an editor UI framework and an asset engine with tree view, scene view and property inspector. Beyond that are all plugins or packages. We designed Fireball to be deeply customizable, even on the game engine side.

Developers can create their own editor and plugins very easily. The editor features are deeply inspired by [Unity](http://unity3d.com/) which we believe has the most advanced game developing editor at the moment.

The desktop version of Fireball is cross-platform powered by [Electron](https://github.com/fireball-x/electron). Currently we test our distribution on Mac and Windows 7/8.1. Issues on other platform are welcome!

Visit [Fireball-x.com](http://www.fireball-x.com) to learn more or visit the Fireball forum.

Want to know what's in our mind for future releases? Check out [Fireball Beta Roadmap](https://github.com/fireball-x/fireball/issues/3).

## Use Distribute Version

1. Download distribute version from [release page](https://github.com/fireball-x/fireball/releases).
2. Extract the zip file to a folder of its own. This folder can locate anywhere on your disk.
3. Click `Fireball.app` on Mac or `fireball.exe` on Windonws to launch fireball.
4. Have fun!

## Use Development Version

Currently the code in development version is not readable, we are truely sorry about that.
We will be refactoring overall project structure during Beta so that we can provide fully readable and commented source code for our engine and editor extension.

### Install

After clone this repo, follow this command:

```bash
cd path/to/repo
bower install
npm install
gulp get
```

### Run

```bash
gulp run
```

### Update

```bash
gulp remove-native-modules
npm install
bower install
gulp get
gulp run
```



## Get Started

Visit http://docs-en.fireball-x.com to learn how to use Fireball Game Engine.

## Feedback & Contribution

- If you have questions about a specific page of documentation, use the disqus sidebar on the left of [Fireball Documentation Site](http://docs-en.fireball-x.com).
- If you have any suggestion/feedback/problem, feel free to [submit an issue](https://github.com/fireball-x/fireball/issues).
- If you want to contribute to this project, please read [Contributing Guidelines](https://github.com/fireball-x/fireball/blob/master/CONTRIBUTING.md).
