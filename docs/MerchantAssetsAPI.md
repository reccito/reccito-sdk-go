# \MerchantAssetsAPI

All URIs are relative to *https://api.reccito.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListOrganisationAssets**](MerchantAssetsAPI.md#ListOrganisationAssets) | **Get** /api/v1/merchant/assets/list | List organisation assets
[**UploadOrganisationBanner**](MerchantAssetsAPI.md#UploadOrganisationBanner) | **Post** /api/v1/merchant/assets/upload/banner | Upload organisation banner
[**UploadOrganisationLogo**](MerchantAssetsAPI.md#UploadOrganisationLogo) | **Post** /api/v1/merchant/assets/upload/logo | Upload organisation logo
[**UploadStoreLogo**](MerchantAssetsAPI.md#UploadStoreLogo) | **Post** /api/v1/merchant/assets/upload/store/logo | Upload store logo



## ListOrganisationAssets

> ApiResponse ListOrganisationAssets(ctx).AssetType(assetType).Execute()

List organisation assets



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
	assetType := "assetType_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantAssetsAPI.ListOrganisationAssets(context.Background()).AssetType(assetType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantAssetsAPI.ListOrganisationAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOrganisationAssets`: ApiResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantAssetsAPI.ListOrganisationAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListOrganisationAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetType** | **string** |  | 

### Return type

[**ApiResponse**](ApiResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadOrganisationBanner

> ApiResponse UploadOrganisationBanner(ctx).File(file).Execute()

Upload organisation banner



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
	file := os.NewFile(1234, "some_file") // *os.File | Banner file to upload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantAssetsAPI.UploadOrganisationBanner(context.Background()).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantAssetsAPI.UploadOrganisationBanner``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadOrganisationBanner`: ApiResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantAssetsAPI.UploadOrganisationBanner`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadOrganisationBannerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** | Banner file to upload | 

### Return type

[**ApiResponse**](ApiResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadOrganisationLogo

> ApiResponse UploadOrganisationLogo(ctx).File(file).Execute()

Upload organisation logo



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
	file := os.NewFile(1234, "some_file") // *os.File | Logo file to upload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantAssetsAPI.UploadOrganisationLogo(context.Background()).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantAssetsAPI.UploadOrganisationLogo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadOrganisationLogo`: ApiResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantAssetsAPI.UploadOrganisationLogo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadOrganisationLogoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** | Logo file to upload | 

### Return type

[**ApiResponse**](ApiResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadStoreLogo

> ApiResponse UploadStoreLogo(ctx).StoreId(storeId).File(file).Execute()

Upload store logo



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
	storeId := "storeId_example" // string | 
	file := os.NewFile(1234, "some_file") // *os.File | Store logo file to upload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MerchantAssetsAPI.UploadStoreLogo(context.Background()).StoreId(storeId).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MerchantAssetsAPI.UploadStoreLogo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadStoreLogo`: ApiResponse
	fmt.Fprintf(os.Stdout, "Response from `MerchantAssetsAPI.UploadStoreLogo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadStoreLogoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **storeId** | **string** |  | 
 **file** | ***os.File** | Store logo file to upload | 

### Return type

[**ApiResponse**](ApiResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

