# ReceiptItemResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Quantity** | **int32** |  | 
**UnitPrice** | **string** |  | 
**TotalPrice** | **string** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**Sku** | Pointer to **NullableString** |  | [optional] 
**Category** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewReceiptItemResponse

`func NewReceiptItemResponse(name string, quantity int32, unitPrice string, totalPrice string, ) *ReceiptItemResponse`

NewReceiptItemResponse instantiates a new ReceiptItemResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptItemResponseWithDefaults

`func NewReceiptItemResponseWithDefaults() *ReceiptItemResponse`

NewReceiptItemResponseWithDefaults instantiates a new ReceiptItemResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ReceiptItemResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ReceiptItemResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ReceiptItemResponse) SetName(v string)`

SetName sets Name field to given value.


### GetQuantity

`func (o *ReceiptItemResponse) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ReceiptItemResponse) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ReceiptItemResponse) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.


### GetUnitPrice

`func (o *ReceiptItemResponse) GetUnitPrice() string`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *ReceiptItemResponse) GetUnitPriceOk() (*string, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *ReceiptItemResponse) SetUnitPrice(v string)`

SetUnitPrice sets UnitPrice field to given value.


### GetTotalPrice

`func (o *ReceiptItemResponse) GetTotalPrice() string`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *ReceiptItemResponse) GetTotalPriceOk() (*string, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *ReceiptItemResponse) SetTotalPrice(v string)`

SetTotalPrice sets TotalPrice field to given value.


### GetDescription

`func (o *ReceiptItemResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ReceiptItemResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ReceiptItemResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ReceiptItemResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ReceiptItemResponse) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ReceiptItemResponse) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetSku

`func (o *ReceiptItemResponse) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *ReceiptItemResponse) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *ReceiptItemResponse) SetSku(v string)`

SetSku sets Sku field to given value.

### HasSku

`func (o *ReceiptItemResponse) HasSku() bool`

HasSku returns a boolean if a field has been set.

### SetSkuNil

`func (o *ReceiptItemResponse) SetSkuNil(b bool)`

 SetSkuNil sets the value for Sku to be an explicit nil

### UnsetSku
`func (o *ReceiptItemResponse) UnsetSku()`

UnsetSku ensures that no value is present for Sku, not even an explicit nil
### GetCategory

`func (o *ReceiptItemResponse) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *ReceiptItemResponse) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *ReceiptItemResponse) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *ReceiptItemResponse) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### SetCategoryNil

`func (o *ReceiptItemResponse) SetCategoryNil(b bool)`

 SetCategoryNil sets the value for Category to be an explicit nil

### UnsetCategory
`func (o *ReceiptItemResponse) UnsetCategory()`

UnsetCategory ensures that no value is present for Category, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


