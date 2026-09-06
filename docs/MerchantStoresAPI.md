# \MerchantStoresAPI

All URIs are relative to *https://api.reccito.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateStore**](MerchantStoresAPI.md#CreateStore) | **Post** /api/v1/merchant/stores | Create Store
[**GetStore**](MerchantStoresAPI.md#GetStore) | **Get** /api/v1/merchant/stores/{store_id} | Get Store
[**GetStoreStats**](MerchantStoresAPI.md#GetStoreStats) | **Get** /api/v1/merchant/stores/{store_id}/stats | Get Store Stats
[**ListStores**](MerchantStoresAPI.md#ListStores) | **Get** /api/v1/merchant/stores | List Stores
[**UpdateStore**](MerchantStoresAPI.md#UpdateStore) | **Put** /api/v1/merchant/stores/{store_id} | Update Store



## CreateStore

> StoreResponse CreateStore(ctx).StoreCreate(storeCreate).Execute()

Create Store



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/reccito/reccito-sdk-go"
)

func main() {
	storeCreate := *openapiclient.NewStoreCreate("Name_example", "Code_example") // StoreCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantStoresAPI.CreateStore(context.Background()).StoreCreate(storeCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantStoresAPI.CreateStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateStore`: StoreResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantStoresAPI.CreateStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **storeCreate** | [**StoreCreate**](StoreCreate.md) |  | 

### Return type

[**StoreResponse**](StoreResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStore

> StoreResponse GetStore(ctx, storeId).Execute()

Get Store



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/reccito/reccito-sdk-go"
)

func main() {
	storeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantStoresAPI.GetStore(context.Background(), storeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantStoresAPI.GetStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStore`: StoreResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantStoresAPI.GetStore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StoreResponse**](StoreResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStoreStats

> StoreStatsResponse GetStoreStats(ctx, storeId).Execute()

Get Store Stats



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/reccito/reccito-sdk-go"
)

func main() {
	storeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantStoresAPI.GetStoreStats(context.Background(), storeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantStoresAPI.GetStoreStats``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStoreStats`: StoreStatsResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantStoresAPI.GetStoreStats`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetStoreStatsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StoreStatsResponse**](StoreStatsResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListStores

> StoreListResponse ListStores(ctx).Skip(skip).Limit(limit).IsActive(isActive).Q(q).Execute()

List Stores



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/reccito/reccito-sdk-go"
)

func main() {
	skip := int32(56) // int32 |  (optional) (default to 0)
	limit := int32(56) // int32 |  (optional) (default to 100)
	isActive := true // bool |  (optional)
	q := "q_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantStoresAPI.ListStores(context.Background()).Skip(skip).Limit(limit).IsActive(isActive).Q(q).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantStoresAPI.ListStores``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListStores`: StoreListResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantStoresAPI.ListStores`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListStoresRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **skip** | **int32** |  | [default to 0]
 **limit** | **int32** |  | [default to 100]
 **isActive** | **bool** |  | 
 **q** | **string** |  | 

### Return type

[**StoreListResponse**](StoreListResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateStore

> StoreResponse UpdateStore(ctx, storeId).StoreUpdate(storeUpdate).Execute()

Update Store



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/reccito/reccito-sdk-go"
)

func main() {
	storeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	storeUpdate := *openapiclient.NewStoreUpdate() // StoreUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantStoresAPI.UpdateStore(context.Background(), storeId).StoreUpdate(storeUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantStoresAPI.UpdateStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateStore`: StoreResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantStoresAPI.UpdateStore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **storeUpdate** | [**StoreUpdate**](StoreUpdate.md) |  | 

### Return type

[**StoreResponse**](StoreResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

