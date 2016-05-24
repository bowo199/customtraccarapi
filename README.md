# traccar

Traccar - JavaScript client for traccar
This SDK is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:

- API version: 3.5
- Package version: 3.5
- Build date: 2016-05-24T14:58:51.734Z
- Build package: class io.swagger.codegen.languages.JavascriptClientCodegen

## Installation

### For [Node.js](https://nodejs.org/)

#### npm

To publish the library as a [npm](https://www.npmjs.com/),
please follow the procedure in ["Publishing npm packages"](https://docs.npmjs.com/getting-started/publishing-npm-packages).

Then install it via:

```shell
npm install traccar --save
```

#### git
#
If the library is hosted at a git repository, e.g.
https://github.com/YOUR_USERNAME/traccar
then install it via:

```shell
npm install YOUR_USERNAME/traccar --save
```

### For browser

The library also works in the browser environment via npm and [browserify](http://browserify.org/). After following
the above steps with Node.js and installing browserify with `npm install -g browserify`,
perform the following (assuming *main.js* is your entry file):

```shell
browserify main.js > bundle.js
```

Then include *bundle.js* in the HTML pages.

## Getting Started

Please follow the [installation](#installation) instruction and execute the following JS code:

```javascript
var Traccar = require('traccar');

var api = new Traccar.DefaultApi()

var body = new Traccar.Command(); // {Command} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.commandsPost(body, callback);

```

## Documentation for API Endpoints

All URIs are relative to *http://demo.traccar.org/api*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*Traccar.DefaultApi* | [**commandsPost**](docs/DefaultApi.md#commandsPost) | **POST** /commands | 
*Traccar.DefaultApi* | [**devicesGet**](docs/DefaultApi.md#devicesGet) | **GET** /devices | 
*Traccar.DefaultApi* | [**devicesIdDelete**](docs/DefaultApi.md#devicesIdDelete) | **DELETE** /devices/{id} | 
*Traccar.DefaultApi* | [**devicesIdPut**](docs/DefaultApi.md#devicesIdPut) | **PUT** /devices/{id} | 
*Traccar.DefaultApi* | [**devicesPost**](docs/DefaultApi.md#devicesPost) | **POST** /devices | 
*Traccar.DefaultApi* | [**groupsGet**](docs/DefaultApi.md#groupsGet) | **GET** /groups | 
*Traccar.DefaultApi* | [**groupsIdDelete**](docs/DefaultApi.md#groupsIdDelete) | **DELETE** /groups/{id} | 
*Traccar.DefaultApi* | [**groupsIdPut**](docs/DefaultApi.md#groupsIdPut) | **PUT** /groups/{id} | 
*Traccar.DefaultApi* | [**groupsPost**](docs/DefaultApi.md#groupsPost) | **POST** /groups | 
*Traccar.DefaultApi* | [**permissionsDevicesDelete**](docs/DefaultApi.md#permissionsDevicesDelete) | **DELETE** /permissions/devices | 
*Traccar.DefaultApi* | [**permissionsDevicesPost**](docs/DefaultApi.md#permissionsDevicesPost) | **POST** /permissions/devices | 
*Traccar.DefaultApi* | [**permissionsGroupsDelete**](docs/DefaultApi.md#permissionsGroupsDelete) | **DELETE** /permissions/groups | 
*Traccar.DefaultApi* | [**permissionsGroupsPost**](docs/DefaultApi.md#permissionsGroupsPost) | **POST** /permissions/groups | 
*Traccar.DefaultApi* | [**positionsGet**](docs/DefaultApi.md#positionsGet) | **GET** /positions | 
*Traccar.DefaultApi* | [**serverGet**](docs/DefaultApi.md#serverGet) | **GET** /server | 
*Traccar.DefaultApi* | [**serverPut**](docs/DefaultApi.md#serverPut) | **PUT** /server | 
*Traccar.DefaultApi* | [**sessionDelete**](docs/DefaultApi.md#sessionDelete) | **DELETE** /session | 
*Traccar.DefaultApi* | [**sessionGet**](docs/DefaultApi.md#sessionGet) | **GET** /session | 
*Traccar.DefaultApi* | [**sessionPost**](docs/DefaultApi.md#sessionPost) | **POST** /session | 
*Traccar.DefaultApi* | [**usersGet**](docs/DefaultApi.md#usersGet) | **GET** /users | 
*Traccar.DefaultApi* | [**usersIdDelete**](docs/DefaultApi.md#usersIdDelete) | **DELETE** /users/{id} | 
*Traccar.DefaultApi* | [**usersIdPut**](docs/DefaultApi.md#usersIdPut) | **PUT** /users/{id} | 
*Traccar.DefaultApi* | [**usersPost**](docs/DefaultApi.md#usersPost) | **POST** /users | 


## Documentation for Models

 - [Traccar.Command](docs/Command.md)
 - [Traccar.Device](docs/Device.md)
 - [Traccar.DevicePermission](docs/DevicePermission.md)
 - [Traccar.Group](docs/Group.md)
 - [Traccar.GroupPermission](docs/GroupPermission.md)
 - [Traccar.Position](docs/Position.md)
 - [Traccar.Server](docs/Server.md)
 - [Traccar.User](docs/User.md)


## Documentation for Authorization

 All endpoints do not require authorization.
