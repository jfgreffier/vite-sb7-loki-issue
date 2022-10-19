# Vue 3 + TypeScript + Vite + Storybook + Loki

## How the project was set up
```
# Chose options : Vue, Typescript
npm create vite@latest

# Storybook 7
npx sb@next init

# Loki install
npm install --save-dev loki
npx loki update
```

## How to run
```sh
npm run storybook
# In parallel, in another terminal
npx loki update
```

Issue
```
loki update v0.30.3
 FAIL  chrome.docker
       Fetching stories
       Cannot call extract() unless you call cacheAllCSFFiles() first.
Some visual tests failed to run
```
