## SPFx-Library-Service-Sample
[How to make spfx-fast-serve work with local dependency packages](https://github.com/s-KaiNet/spfx-fast-serve/issues/5)

[How to set context for pnpjs in Service ?](https://github.com/pnp/pnpjs/issues/869)

### Building the code
* Change Site Url in src\SPFx-WebPart\Config\serve.json
* In Termainal 1
    * cd src\SPFx-Library
    * npm install
    * gulp serve
* In Terminal 2
    * cd src\SPFx-WebPart
    * npm install
    * gulp serve
* Edit the page (NOT online workbench) and add Sample WebPart