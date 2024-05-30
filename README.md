# JS/TS Monorepos

# DEBUG NOTES: 
1) copy fixed_node_modules to node_modules
the modifications to xxx.d.ts files are different than what is in the video

COURSE_FILES are missing 01-03 sections. Go to the original repo to get them.
These containe the types and utils directories

branch dc is completed up to Yarn2 and Dependencies Q&A

> cd packages/types 
> yarn install; yarn build
> yarn jest
> cd packages/utils
> yarn install; yarn build
> yarn jest


### Tools

Next, make sure you have installed [volta](http://volta.sh/) which ensures you have the right version of node and yarn for this project. You can run:
```
volta install node
```
and then:
```
volta install yarn
```
To get the right versions for this workshop.

### volta pin yarn node



### Install dependencies

[`yarn`](https://yarnpkg.com/) is the recommended package manager to use with this project. Please use it instead of npm.

Install dependencies with yarn by running

```sh
yarn
```

### Starting the project

Start up the project in development mode by running

```sh
yarn dev
```

Changing any files in the `src` folder will result in an incremental rebuild, and a refresh of the screen.

By default, the app is served on https://localhost:1234.
