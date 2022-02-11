Sample project to test `@truffle/fetch-and-compile`

1. `git clone git@github.com:cds-amal/exp-fetch-and-compile.git`
1. `yarn`

If you're using the latest npmjs release @truffle/fetch-and-compile you're 
good to go. However if you want to modify @truffle/fetch-and-compile, you 
have to set up `yarn link` See below, otherwise...

3. tsc # does the project build?


## building @truffle/fetch-and-compile from the truffle monorepo

Set up yarn link (source side)

  - cd to truffle_root
  - yarn bootstrap
  - cd packages/fetch-and-compile
  - yarn link

Set up client side
  - cd to exp-fetch-and-compile
  - yarn link @truffle/fetch-and-compile

