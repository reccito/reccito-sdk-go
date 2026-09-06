# ReceiptImmediateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**PublicToken** | **string** |  | 
**Barcode** | Pointer to [**NullableBarcode**](Barcode.md) |  | [optional] 
**MerchantReceiptId** | Pointer to **NullableString** |  | [optional] 
**StoreId** | **string** |  | 
**OrganisationId** | **string** |  | 
**QrCodeUrl** | **string** |  | 
**QrToken** | **string** |  | 
**QrExpiresAt** | **NullableTime** |  | 
**ReceiptUrl** | **string** |  | 
**TransactionDate** | **time.Time** |  | 
**TotalAmount** | **string** |  | 
**Currency** | **string** |  | 
**ProcessingStatus** | Pointer to **string** |  | [optional] [default to "processing"]
**CreatedAt** | **time.Time** |  | 

## Methods

### NewReceiptImmediateResponse

`func NewReceiptImmediateResponse(id string, publicToken string, storeId string, organisationId string, qrCodeUrl string, qrToken string, qrExpiresAt NullableTime, receiptUrl string, transactionDate time.Time, totalAmount string, currency string, createdAt time.Time, ) *ReceiptImmediateResponse`

NewReceiptImmediateResponse instantiates a new ReceiptImmediateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptImmediateResponseWithDefaults

`func NewReceiptImmediateResponseWithDefaults() *ReceiptImmediateResponse`

NewReceiptImmediateResponseWithDefaults instantiates a new ReceiptImmediateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ReceiptImmediateResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ReceiptImmediateResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ReceiptImmediateResponse) SetId(v string)`

SetId sets Id field to given value.


### GetPublicToken

`func (o *ReceiptImmediateResponse) GetPublicToken() string`

GetPublicToken returns the PublicToken field if non-nil, zero value otherwise.

### GetPublicTokenOk

`func (o *ReceiptImmediateResponse) GetPublicTokenOk() (*string, bool)`

GetPublicTokenOk returns a tuple with the PublicToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicToken

`func (o *ReceiptImmediateResponse) SetPublicToken(v string)`

SetPublicToken sets PublicToken field to given value.


### GetBarcode

`func (o *ReceiptImmediateResponse) GetBarcode() Barcode`

GetBarcode returns the Barcode field if non-nil, zero value otherwise.

### GetBarcodeOk

`func (o *ReceiptImmediateResponse) GetBarcodeOk() (*Barcode, bool)`

GetBarcodeOk returns a tuple with the Barcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBarcode

`func (o *ReceiptImmediateResponse) SetBarcode(v Barcode)`

SetBarcode sets Barcode field to given value.

### HasBarcode

`func (o *ReceiptImmediateResponse) HasBarcode() bool`

HasBarcode returns a boolean if a field has been set.

### SetBarcodeNil

`func (o *ReceiptImmediateResponse) SetBarcodeNil(b bool)`

 SetBarcodeNil sets the value for Barcode to be an explicit nil

### UnsetBarcode
`func (o *ReceiptImmediateResponse) UnsetBarcode()`

UnsetBarcode ensures that no value is present for Barcode, not even an explicit nil
### GetMerchantReceiptId

`func (o *ReceiptImmediateResponse) GetMerchantReceiptId() string`

GetMerchantReceiptId returns the MerchantReceiptId field if non-nil, zero value otherwise.

### GetMerchantReceiptIdOk

`func (o *ReceiptImmediateResponse) GetMerchantReceiptIdOk() (*string, bool)`

GetMerchantReceiptIdOk returns a tuple with the MerchantReceiptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantReceiptId

`func (o *ReceiptImmediateResponse) SetMerchantReceiptId(v string)`

SetMerchantReceiptId sets MerchantReceiptId field to given value.

### HasMerchantReceiptId

`func (o *ReceiptImmediateResponse) HasMerchantReceiptId() bool`

HasMerchantReceiptId returns a boolean if a field has been set.

### SetMerchantReceiptIdNil

`func (o *ReceiptImmediateResponse) SetMerchantReceiptIdNil(b bool)`

 SetMerchantReceiptIdNil sets the value for MerchantReceiptId to be an explicit nil

### UnsetMerchantReceiptId
`func (o *ReceiptImmediateResponse) UnsetMerchantReceiptId()`

UnsetMerchantReceiptId ensures that no value is present for MerchantReceiptId, not even an explicit nil
### GetStoreId

`func (o *ReceiptImmediateResponse) GetStoreId() string`

GetStoreId returns the StoreId field if non-nil, zero value otherwise.

### GetStoreIdOk

`func (o *ReceiptImmediateResponse) GetStoreIdOk() (*string, bool)`

GetStoreIdOk returns a tuple with the StoreId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreId

`func (o *ReceiptImmediateResponse) SetStoreId(v string)`

SetStoreId sets StoreId field to given value.


### GetOrganisationId

`func (o *ReceiptImmediateResponse) GetOrganisationId() string`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *ReceiptImmediateResponse) GetOrganisationIdOk() (*string, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *ReceiptImmediateResponse) SetOrganisationId(v string)`

SetOrganisationId sets OrganisationId field to given value.


### GetQrCodeUrl

`func (o *ReceiptImmediateResponse) GetQrCodeUrl() string`

GetQrCodeUrl returns the QrCodeUrl field if non-nil, zero value otherwise.

### GetQrCodeUrlOk

`func (o *ReceiptImmediateResponse) GetQrCodeUrlOk() (*string, bool)`

GetQrCodeUrlOk returns a tuple with the QrCodeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeUrl

`func (o *ReceiptImmediateResponse) SetQrCodeUrl(v string)`

SetQrCodeUrl sets QrCodeUrl field to given value.


### GetQrToken

`func (o *ReceiptImmediateResponse) GetQrToken() string`

GetQrToken returns the QrToken field if non-nil, zero value otherwise.

### GetQrTokenOk

`func (o *ReceiptImmediateResponse) GetQrTokenOk() (*string, bool)`

GetQrTokenOk returns a tuple with the QrToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrToken

`func (o *ReceiptImmediateResponse) SetQrToken(v string)`

SetQrToken sets QrToken field to given value.


### GetQrExpiresAt

`func (o *ReceiptImmediateResponse) GetQrExpiresAt() time.Time`

GetQrExpiresAt returns the QrExpiresAt field if non-nil, zero value otherwise.

### GetQrExpiresAtOk

`func (o *ReceiptImmediateResponse) GetQrExpiresAtOk() (*time.Time, bool)`

GetQrExpiresAtOk returns a tuple with the QrExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrExpiresAt

`func (o *ReceiptImmediateResponse) SetQrExpiresAt(v time.Time)`

SetQrExpiresAt sets QrExpiresAt field to given value.


### SetQrExpiresAtNil

`func (o *ReceiptImmediateResponse) SetQrExpiresAtNil(b bool)`

 SetQrExpiresAtNil sets the value for QrExpiresAt to be an explicit nil

### UnsetQrExpiresAt
`func (o *ReceiptImmediateResponse) UnsetQrExpiresAt()`

UnsetQrExpiresAt ensures that no value is present for QrExpiresAt, not even an explicit nil
### GetReceiptUrl

`func (o *ReceiptImmediateResponse) GetReceiptUrl() string`

GetReceiptUrl returns the ReceiptUrl field if non-nil, zero value otherwise.

### GetReceiptUrlOk

`func (o *ReceiptImmediateResponse) GetReceiptUrlOk() (*string, bool)`

GetReceiptUrlOk returns a tuple with the ReceiptUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptUrl

`func (o *ReceiptImmediateResponse) SetReceiptUrl(v string)`

SetReceiptUrl sets ReceiptUrl field to given value.


### GetTransactionDate

`func (o *ReceiptImmediateResponse) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *ReceiptImmediateResponse) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *ReceiptImmediateResponse) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.


### GetTotalAmount

`func (o *ReceiptImmediateResponse) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *ReceiptImmediateResponse) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *ReceiptImmediateResponse) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.


### GetCurrency

`func (o *ReceiptImmediateResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ReceiptImmediateResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ReceiptImmediateResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetProcessingStatus

`func (o *ReceiptImmediateResponse) GetProcessingStatus() string`

GetProcessingStatus returns the ProcessingStatus field if non-nil, zero value otherwise.

### GetProcessingStatusOk

`func (o *ReceiptImmediateResponse) GetProcessingStatusOk() (*string, bool)`

GetProcessingStatusOk returns a tuple with the ProcessingStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingStatus

`func (o *ReceiptImmediateResponse) SetProcessingStatus(v string)`

SetProcessingStatus sets ProcessingStatus field to given value.

### HasProcessingStatus

`func (o *ReceiptImmediateResponse) HasProcessingStatus() bool`

HasProcessingStatus returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ReceiptImmediateResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ReceiptImmediateResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ReceiptImmediateResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


