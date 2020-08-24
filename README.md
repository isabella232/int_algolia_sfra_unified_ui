# int_algolia_sfra_unified_ui

## Setup

1. Clone this repository including git submodules
    ```sh
    $ git clone --recurse-submodules https://github.com/algolia/int_algolia_sfra_unified_ui 
    ```
2. install dependencies
    ```sh
    $ cd int_algolia_sfra_unified_ui 
    $ npm install && npm install --prefix unified-instantsearch-ecommerce
    ```

3. compile & export Unified UI
    ```sh
    $ npm run --prefix unified-instantsearch-ecommerce export
    ```
   
4. upload the cartridge
    ```sh
    $ npm run uploadCartridge
    ```

