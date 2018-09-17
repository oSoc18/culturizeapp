# The Culturize App

This is the GitHub repo of the Culturize App Project of oSoC18.

![CulturizeLogo](https://github.com/oSoc18/culturizeapp/blob/master/static/assets/logo-culturize.png)



* Content:
  * [Website](https://osoc18.github.io/culturize/)
  * [Setup](https://github.com/oSoc18/culturizeapp/blob/master/doc/Setup.md): Learn how to setup a fork of the app and run it!
  * [Coding Style](https://github.com/oSoc18/culturizeapp/blob/master/doc/Style.md): Read this before contributing to the project.
  * [Bugs and Features idea list](https://github.com/oSoc18/culturizeapp/blob/master/doc/Possible%20Improvements.md)
  * [Explanation of the 4 Components of the Toolchain](https://github.com/oSoc18/culturizeapp/blob/master/doc/pdf/components.pdf)
  * [In-depth explanation of the internal flow of the app](https://github.com/oSoc18/culturizeapp/blob/master/doc/pdf/flow.pdf)
  * Source code: the Source code for the HTML pages is contained in the [static](https://github.com/oSoc18/culturizeapp/tree/master/static) folder, and the source code for the core logic in the [src](https://github.com/oSoc18/culturizeapp/tree/master/src) folder. 

## Example input CSV

The input CSV can look as follows:
```
PID,document type,URL,enabled
ID_1,data,http://example.org,true
```
Note:
* `document type` value can be choosen freely, but it is recommended to follow URI [guidelines](https://www.projectcest.be/wiki/Publicatie:Project_Persistente_identificatie) (data, work, id...)
* `enabled` is optional
* column names can be configured inside `culturize.conf.ts`
