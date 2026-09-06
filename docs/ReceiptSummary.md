# ReceiptSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**PublicToken** | **string** |  | 
**MerchantReceiptId** | Pointer to **NullableString** |  | [optional] 
**StoreId** | **string** |  | 
**OrganisationId** | **string** |  | 
**TransactionDate** | **time.Time** |  | 
**TotalAmount** | **string** |  | 
**Currency** | **string** |  | 
**ItemCount** | **int32** |  | 
**Status** | **string** |  | 
**AccessCount** | **int32** |  | 
**ReceiptUrl** | **string** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewReceiptSummary

`func NewReceiptSummary(id string, publicToken string, storeId string, organisationId string, transactionDate time.Time, totalAmount string, currency string, itemCount int32, status string, accessCount int32, receiptUrl string, createdAt time.Time, ) *ReceiptSummary`

NewReceiptSummary instantiates a new ReceiptSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptSummaryWithDefaults

`func NewReceiptSummaryWithDefaults() *ReceiptSummary`

NewReceiptSummaryWithDefaults instantiates a new ReceiptSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ReceiptSummary) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ReceiptSummary) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ReceiptSummary) SetId(v string)`

SetId sets Id field to given value.


### GetPublicToken

`func (o *ReceiptSummary) GetPublicToken() string`

GetPublicToken returns the PublicToken field if non-nil, zero value otherwise.

### GetPublicTokenOk

`func (o *ReceiptSummary) GetPublicTokenOk() (*string, bool)`

GetPublicTokenOk returns a tuple with the PublicToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicToken

`func (o *ReceiptSummary) SetPublicToken(v string)`

SetPublicToken sets PublicToken field to given value.


### GetMerchantReceiptId

`func (o *ReceiptSummary) GetMerchantReceiptId() string`

GetMerchantReceiptId returns the MerchantReceiptId field if non-nil, zero value otherwise.

### GetMerchantReceiptIdOk

`func (o *ReceiptSummary) GetMerchantReceiptIdOk() (*string, bool)`

GetMerchantReceiptIdOk returns a tuple with the MerchantReceiptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantReceiptId

`func (o *ReceiptSummary) SetMerchantReceiptId(v string)`

SetMerchantReceiptId sets MerchantReceiptId field to given value.

### HasMerchantReceiptId

`func (o *ReceiptSummary) HasMerchantReceiptId() bool`

HasMerchantReceiptId returns a boolean if a field has been set.

### SetMerchantReceiptIdNil

`func (o *ReceiptSummary) SetMerchantReceiptIdNil(b bool)`

 SetMerchantReceiptIdNil sets the value for MerchantReceiptId to be an explicit nil

### UnsetMerchantReceiptId
`func (o *ReceiptSummary) UnsetMerchantReceiptId()`

UnsetMerchantReceiptId ensures that no value is present for MerchantReceiptId, not even an explicit nil
### GetStoreId

`func (o *ReceiptSummary) GetStoreId() string`

GetStoreId returns the StoreId field if non-nil, zero value otherwise.

### GetStoreIdOk

`func (o *ReceiptSummary) GetStoreIdOk() (*string, bool)`

GetStoreIdOk returns a tuple with the StoreId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreId

`func (o *ReceiptSummary) SetStoreId(v string)`

SetStoreId sets StoreId field to given value.


### GetOrganisationId

`func (o *ReceiptSummary) GetOrganisationId() string`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *ReceiptSummary) GetOrganisationIdOk() (*string, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *ReceiptSummary) SetOrganisationId(v string)`

SetOrganisationId sets OrganisationId field to given value.


### GetTransactionDate

`func (o *ReceiptSummary) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *ReceiptSummary) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *ReceiptSummary) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.


### GetTotalAmount

`func (o *ReceiptSummary) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *ReceiptSummary) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *ReceiptSummary) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.


### GetCurrency

`func (o *ReceiptSummary) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ReceiptSummary) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ReceiptSummary) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetItemCount

`func (o *ReceiptSummary) GetItemCount() int32`

GetItemCount returns the ItemCount field if non-nil, zero value otherwise.

### GetItemCountOk

`func (o *ReceiptSummary) GetItemCountOk() (*int32, bool)`

GetItemCountOk returns a tuple with the ItemCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemCount

`func (o *ReceiptSummary) SetItemCount(v int32)`

SetItemCount sets ItemCount field to given value.


### GetStatus

`func (o *ReceiptSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ReceiptSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ReceiptSummary) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAccessCount

`func (o *ReceiptSummary) GetAccessCount() int32`

GetAccessCount returns the AccessCount field if non-nil, zero value otherwise.

### GetAccessCountOk

`func (o *ReceiptSummary) GetAccessCountOk() (*int32, bool)`

GetAccessCountOk returns a tuple with the AccessCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessCount

`func (o *ReceiptSummary) SetAccessCount(v int32)`

SetAccessCount sets AccessCount field to given value.


### GetReceiptUrl

`func (o *ReceiptSummary) GetReceiptUrl() string`

GetReceiptUrl returns the ReceiptUrl field if non-nil, zero value otherwise.

### GetReceiptUrlOk

`func (o *ReceiptSummary) GetReceiptUrlOk() (*string, bool)`

GetReceiptUrlOk returns a tuple with the ReceiptUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptUrl

`func (o *ReceiptSummary) SetReceiptUrl(v string)`

SetReceiptUrl sets ReceiptUrl field to given value.


### GetCreatedAt

`func (o *ReceiptSummary) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ReceiptSummary) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ReceiptSummary) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


