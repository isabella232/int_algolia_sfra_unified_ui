# int_algolia_sfra_unified_ui

## Setup

`sh
# clone the repo
$ git clone --recurse-submodules https://github.com/algolia/int_algolia_sfra_unified_ui 
$ cd int_algolia_sfra_unified_ui 

# install dependencies
$ npm install && npm install --prefix unified-instantsearch-ecommerce

# compile & export Unified UI
$ npm run --prefix unified-instantsearch-ecommerce export

# upload the cartridge
$ npm run uploadCartridge
`
