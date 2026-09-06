# \MerchantReceiptsAPI

All URIs are relative to *https://api.reccito.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateReceipt**](MerchantReceiptsAPI.md#CreateReceipt) | **Post** /api/v1/merchant/receipts | Create Receipt
[**GetReceipt**](MerchantReceiptsAPI.md#GetReceipt) | **Get** /api/v1/merchant/receipts/{receipt_id} | Get Receipt
[**ListReceipts**](MerchantReceiptsAPI.md#ListReceipts) | **Get** /api/v1/merchant/receipts | List Receipts
[**RefreshReceiptQr**](MerchantReceiptsAPI.md#RefreshReceiptQr) | **Put** /api/v1/merchant/receipts/{receipt_id}/refresh-qr | Refresh Qr Code



## CreateReceipt

> ReceiptImmediateResponse CreateReceipt(ctx).ReceiptCreate(receiptCreate).Execute()

Create Receipt



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/reccito/reccito-sdk-go"
)

func main() {
	receiptCreate := *openapiclient.NewReceiptCreate(time.Now(), []openapiclient.ReceiptItemCreate{*openapiclient.NewReceiptItemCreate("Name_example", int32(123), "12.99", "12.99")}, "12.99", "12.99", "12.99", "Currency_example", []openapiclient.PaymentInfoCreate{*openapiclient.NewPaymentInfoCreate("Method_example", "12.99")}) // ReceiptCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantReceiptsAPI.CreateReceipt(context.Background()).ReceiptCreate(receiptCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantReceiptsAPI.CreateReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateReceipt`: ReceiptImmediateResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantReceiptsAPI.CreateReceipt`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **receiptCreate** | [**ReceiptCreate**](ReceiptCreate.md) |  | 

### Return type

[**ReceiptImmediateResponse**](ReceiptImmediateResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetReceipt

> MerchantReceiptResponse GetReceipt(ctx, receiptId).Execute()

Get Receipt



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
	receiptId := "receiptId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantReceiptsAPI.GetReceipt(context.Background(), receiptId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantReceiptsAPI.GetReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetReceipt`: MerchantReceiptResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantReceiptsAPI.GetReceipt`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**receiptId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MerchantReceiptResponse**](MerchantReceiptResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListReceipts

> ReceiptListResponse ListReceipts(ctx).Page(page).Limit(limit).StoreId(storeId).Status(status).Search(search).SortBy(sortBy).SortOrder(sortOrder).Execute()

List Receipts



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
	page := int32(56) // int32 |  (optional) (default to 1)
	limit := int32(56) // int32 |  (optional) (default to 50)
	storeId := "storeId_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	search := "search_example" // string |  (optional)
	sortBy := "sortBy_example" // string |  (optional) (default to "created_at")
	sortOrder := "sortOrder_example" // string |  (optional) (default to "desc")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantReceiptsAPI.ListReceipts(context.Background()).Page(page).Limit(limit).StoreId(storeId).Status(status).Search(search).SortBy(sortBy).SortOrder(sortOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantReceiptsAPI.ListReceipts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListReceipts`: ReceiptListResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantReceiptsAPI.ListReceipts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListReceiptsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | [default to 1]
 **limit** | **int32** |  | [default to 50]
 **storeId** | **string** |  | 
 **status** | **string** |  | 
 **search** | **string** |  | 
 **sortBy** | **string** |  | [default to &quot;created_at&quot;]
 **sortOrder** | **string** |  | [default to &quot;desc&quot;]

### Return type

[**ReceiptListResponse**](ReceiptListResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RefreshReceiptQr

> QRRefreshResponse RefreshReceiptQr(ctx, receiptId).Execute()

Refresh Qr Code



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
	receiptId := "receiptId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantReceiptsAPI.RefreshReceiptQr(context.Background(), receiptId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantReceiptsAPI.RefreshReceiptQr``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefreshReceiptQr`: QRRefreshResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantReceiptsAPI.RefreshReceiptQr`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**receiptId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRefreshReceiptQrRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**QRRefreshResponse**](QRRefreshResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

