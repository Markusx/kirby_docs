
<a name="delete_account_by_id"></a>
### Deletes an Account by ID.
```
DELETE /accounts/{id}
```


#### Parameters

|Type|Name|Description|Schema|
|---|---|---|---|
|**Header**|**x-api-key**  <br>*required*|The API key belonging to the calling client.|string|
|**Header**|**x-gw-ims-org-id**  <br>*required*|The owning IMS organization identifier.|string|
|**Path**|**id**  <br>*required*|Object ID|string|


#### Responses

|HTTP Code|Description|Schema|
|---|---|---|
|**200**|Array[ @/accounts/accountId ]|< string > array|
|**400**|Bad request|No Content|
|**403**|Forbidden|No Content|
|**404**|Not found|No Content|
|**500**|Internal server error|No Content|
|**default**|Unexpected error|No Content|


#### Consumes

* `application/json`


#### Produces

* `application/json`


#### Security

|Type|Name|
|---|---|
|**apiKey**|**[Bearer](security.md#bearer)**|


#### Example HTTP request

##### Request path
```
/accounts/string
```


##### Request header
```
json :
"string"
```


#### Example HTTP response

##### Response 200
```
json :
[ "string" ]
```



