# Traccar.DefaultApi

All URIs are relative to *http://demo.traccar.org/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**commandsPost**](DefaultApi.md#commandsPost) | **POST** /commands | 
[**devicesGet**](DefaultApi.md#devicesGet) | **GET** /devices | 
[**devicesIdDelete**](DefaultApi.md#devicesIdDelete) | **DELETE** /devices/{id} | 
[**devicesIdPut**](DefaultApi.md#devicesIdPut) | **PUT** /devices/{id} | 
[**devicesPost**](DefaultApi.md#devicesPost) | **POST** /devices | 
[**groupsGet**](DefaultApi.md#groupsGet) | **GET** /groups | 
[**groupsIdDelete**](DefaultApi.md#groupsIdDelete) | **DELETE** /groups/{id} | 
[**groupsIdPut**](DefaultApi.md#groupsIdPut) | **PUT** /groups/{id} | 
[**groupsPost**](DefaultApi.md#groupsPost) | **POST** /groups | 
[**permissionsDevicesDelete**](DefaultApi.md#permissionsDevicesDelete) | **DELETE** /permissions/devices | 
[**permissionsDevicesPost**](DefaultApi.md#permissionsDevicesPost) | **POST** /permissions/devices | 
[**permissionsGroupsDelete**](DefaultApi.md#permissionsGroupsDelete) | **DELETE** /permissions/groups | 
[**permissionsGroupsPost**](DefaultApi.md#permissionsGroupsPost) | **POST** /permissions/groups | 
[**positionsGet**](DefaultApi.md#positionsGet) | **GET** /positions | 
[**serverGet**](DefaultApi.md#serverGet) | **GET** /server | 
[**serverPut**](DefaultApi.md#serverPut) | **PUT** /server | 
[**sessionDelete**](DefaultApi.md#sessionDelete) | **DELETE** /session | 
[**sessionGet**](DefaultApi.md#sessionGet) | **GET** /session | 
[**sessionPost**](DefaultApi.md#sessionPost) | **POST** /session | 
[**usersGet**](DefaultApi.md#usersGet) | **GET** /users | 
[**usersIdDelete**](DefaultApi.md#usersIdDelete) | **DELETE** /users/{id} | 
[**usersIdPut**](DefaultApi.md#usersIdPut) | **PUT** /users/{id} | 
[**usersPost**](DefaultApi.md#usersPost) | **POST** /users | 


<a name="commandsPost"></a>
# **commandsPost**
> Command commandsPost(body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

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

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**Command**](Command.md)|  | 

### Return type

[**Command**](Command.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="devicesGet"></a>
# **devicesGet**
> [Device] devicesGet(all, userId)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var all = true; // {Boolean} 

var userId = 56; // {Integer} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.devicesGet(all, userId, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **all** | **Boolean**|  | 
 **userId** | [**Integer**](.md)|  | 

### Return type

[**[Device]**](Device.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="devicesIdDelete"></a>
# **devicesIdDelete**
> devicesIdDelete(id)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var id = 56; // {Integer} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
};
api.devicesIdDelete(id, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | [**Integer**](.md)|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="devicesIdPut"></a>
# **devicesIdPut**
> Device devicesIdPut(id, body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var id = 56; // {Integer} 

var body = new Traccar.Device(); // {Device} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.devicesIdPut(id, body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | [**Integer**](.md)|  | 
 **body** | [**Device**](Device.md)|  | 

### Return type

[**Device**](Device.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="devicesPost"></a>
# **devicesPost**
> Device devicesPost(body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var body = new Traccar.Device(); // {Device} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.devicesPost(body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**Device**](Device.md)|  | 

### Return type

[**Device**](Device.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="groupsGet"></a>
# **groupsGet**
> [Group] groupsGet(all, userId)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var all = true; // {Boolean} 

var userId = 56; // {Integer} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.groupsGet(all, userId, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **all** | **Boolean**|  | 
 **userId** | [**Integer**](.md)|  | 

### Return type

[**[Group]**](Group.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="groupsIdDelete"></a>
# **groupsIdDelete**
> groupsIdDelete(id)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var id = 56; // {Integer} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
};
api.groupsIdDelete(id, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | [**Integer**](.md)|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="groupsIdPut"></a>
# **groupsIdPut**
> Group groupsIdPut(id, body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var id = 56; // {Integer} 

var body = new Traccar.Group(); // {Group} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.groupsIdPut(id, body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | [**Integer**](.md)|  | 
 **body** | [**Group**](Group.md)|  | 

### Return type

[**Group**](Group.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="groupsPost"></a>
# **groupsPost**
> Group groupsPost(body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var body = new Traccar.Group(); // {Group} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.groupsPost(body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**Group**](Group.md)|  | 

### Return type

[**Group**](Group.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="permissionsDevicesDelete"></a>
# **permissionsDevicesDelete**
> permissionsDevicesDelete(body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var body = new Traccar.DevicePermission(); // {DevicePermission} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
};
api.permissionsDevicesDelete(body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**DevicePermission**](DevicePermission.md)|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="permissionsDevicesPost"></a>
# **permissionsDevicesPost**
> DevicePermission permissionsDevicesPost(body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var body = new Traccar.DevicePermission(); // {DevicePermission} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.permissionsDevicesPost(body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**DevicePermission**](DevicePermission.md)|  | 

### Return type

[**DevicePermission**](DevicePermission.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="permissionsGroupsDelete"></a>
# **permissionsGroupsDelete**
> permissionsGroupsDelete(body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var body = new Traccar.GroupPermission(); // {GroupPermission} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
};
api.permissionsGroupsDelete(body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**GroupPermission**](GroupPermission.md)|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="permissionsGroupsPost"></a>
# **permissionsGroupsPost**
> GroupPermission permissionsGroupsPost(body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var body = new Traccar.GroupPermission(); // {GroupPermission} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.permissionsGroupsPost(body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**GroupPermission**](GroupPermission.md)|  | 

### Return type

[**GroupPermission**](GroupPermission.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="positionsGet"></a>
# **positionsGet**
> [Position] positionsGet(deviceId, from, to)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var deviceId = 56; // {Integer} 

var from = "from_example"; // {String} 

var to = "to_example"; // {String} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.positionsGet(deviceId, from, to, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deviceId** | [**Integer**](.md)|  | 
 **from** | **String**|  | 
 **to** | **String**|  | 

### Return type

[**[Position]**](Position.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="serverGet"></a>
# **serverGet**
> Server serverGet



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.serverGet(callback);
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**Server**](Server.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="serverPut"></a>
# **serverPut**
> Server serverPut(body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var body = new Traccar.Server(); // {Server} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.serverPut(body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**Server**](Server.md)|  | 

### Return type

[**Server**](Server.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="sessionDelete"></a>
# **sessionDelete**
> sessionDelete



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
};
api.sessionDelete(callback);
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/x-www-form-urlencoded
 - **Accept**: application/json

<a name="sessionGet"></a>
# **sessionGet**
> User sessionGet



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.sessionGet(callback);
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/x-www-form-urlencoded
 - **Accept**: application/json

<a name="sessionPost"></a>
# **sessionPost**
> User sessionPost(email, password)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var email = "email_example"; // {String} 

var password = "password_example"; // {String} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.sessionPost(email, password, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **email** | **String**|  | 
 **password** | **String**|  | 

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/x-www-form-urlencoded
 - **Accept**: application/json

<a name="usersGet"></a>
# **usersGet**
> [Position] usersGet



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.usersGet(callback);
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[Position]**](Position.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="usersIdDelete"></a>
# **usersIdDelete**
> usersIdDelete(id)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var id = 56; // {Integer} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
};
api.usersIdDelete(id, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | [**Integer**](.md)|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="usersIdPut"></a>
# **usersIdPut**
> User usersIdPut(id, body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var id = 56; // {Integer} 

var body = new Traccar.User(); // {User} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.usersIdPut(id, body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | [**Integer**](.md)|  | 
 **body** | [**User**](User.md)|  | 

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="usersPost"></a>
# **usersPost**
> User usersPost(body)



### Example
```javascript
var Traccar = require('traccar');

var apiInstance = new Traccar.DefaultApi()

var body = new Traccar.User(); // {User} 


var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
api.usersPost(body, callback);
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**User**](User.md)|  | 

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP reuqest headers

 - **Content-Type**: application/json
 - **Accept**: application/json

