To show the issue, after running the following gatsby should start fully.  Notice that onPreInit is not called which does a log and process.exit

```
yarn
yarn develop
```

To fix the issue, edit package.json and change `xalias` to `alias` then run


```
yarn develop
```
