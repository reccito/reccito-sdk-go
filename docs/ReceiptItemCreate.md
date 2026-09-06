# ReceiptItemCreate

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

### NewReceiptItemCreate

`func NewReceiptItemCreate(name string, quantity int32, unitPrice string, totalPrice string, ) *ReceiptItemCreate`

NewReceiptItemCreate instantiates a new ReceiptItemCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptItemCreateWithDefaults

`func NewReceiptItemCreateWithDefaults() *ReceiptItemCreate`

NewReceiptItemCreateWithDefaults instantiates a new ReceiptItemCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ReceiptItemCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ReceiptItemCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ReceiptItemCreate) SetName(v string)`

SetName sets Name field to given value.


### GetQuantity

`func (o *ReceiptItemCreate) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ReceiptItemCreate) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ReceiptItemCreate) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.


### GetUnitPrice

`func (o *ReceiptItemCreate) GetUnitPrice() string`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *ReceiptItemCreate) GetUnitPriceOk() (*string, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *ReceiptItemCreate) SetUnitPrice(v string)`

SetUnitPrice sets UnitPrice field to given value.


### GetTotalPrice

`func (o *ReceiptItemCreate) GetTotalPrice() string`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *ReceiptItemCreate) GetTotalPriceOk() (*string, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *ReceiptItemCreate) SetTotalPrice(v string)`

SetTotalPrice sets TotalPrice field to given value.


### GetDescription

`func (o *ReceiptItemCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ReceiptItemCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ReceiptItemCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ReceiptItemCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ReceiptItemCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ReceiptItemCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetSku

`func (o *ReceiptItemCreate) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *ReceiptItemCreate) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *ReceiptItemCreate) SetSku(v string)`

SetSku sets Sku field to given value.

### HasSku

`func (o *ReceiptItemCreate) HasSku() bool`

HasSku returns a boolean if a field has been set.

### SetSkuNil

`func (o *ReceiptItemCreate) SetSkuNil(b bool)`

 SetSkuNil sets the value for Sku to be an explicit nil

### UnsetSku
`func (o *ReceiptItemCreate) UnsetSku()`

UnsetSku ensures that no value is present for Sku, not even an explicit nil
### GetCategory

`func (o *ReceiptItemCreate) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *ReceiptItemCreate) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *ReceiptItemCreate) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *ReceiptItemCreate) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### SetCategoryNil

`func (o *ReceiptItemCreate) SetCategoryNil(b bool)`

 SetCategoryNil sets the value for Category to be an explicit nil

### UnsetCategory
`func (o *ReceiptItemCreate) UnsetCategory()`

UnsetCategory ensures that no value is present for Category, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


