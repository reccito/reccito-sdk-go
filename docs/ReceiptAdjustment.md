# ReceiptAdjustment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Scope** | Pointer to **string** |  | [optional] [default to "receipt"]
**Kind** | **string** |  | 
**Label** | Pointer to **NullableString** |  | [optional] 
**Amount** | **string** |  | 
**ItemName** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewReceiptAdjustment

`func NewReceiptAdjustment(kind string, amount string, ) *ReceiptAdjustment`

NewReceiptAdjustment instantiates a new ReceiptAdjustment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptAdjustmentWithDefaults

`func NewReceiptAdjustmentWithDefaults() *ReceiptAdjustment`

NewReceiptAdjustmentWithDefaults instantiates a new ReceiptAdjustment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetScope

`func (o *ReceiptAdjustment) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *ReceiptAdjustment) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *ReceiptAdjustment) SetScope(v string)`

SetScope sets Scope field to given value.

### HasScope

`func (o *ReceiptAdjustment) HasScope() bool`

HasScope returns a boolean if a field has been set.

### GetKind

`func (o *ReceiptAdjustment) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ReceiptAdjustment) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ReceiptAdjustment) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLabel

`func (o *ReceiptAdjustment) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ReceiptAdjustment) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ReceiptAdjustment) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *ReceiptAdjustment) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *ReceiptAdjustment) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *ReceiptAdjustment) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetAmount

`func (o *ReceiptAdjustment) GetAmount() string`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *ReceiptAdjustment) GetAmountOk() (*string, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *ReceiptAdjustment) SetAmount(v string)`

SetAmount sets Amount field to given value.


### GetItemName

`func (o *ReceiptAdjustment) GetItemName() string`

GetItemName returns the ItemName field if non-nil, zero value otherwise.

### GetItemNameOk

`func (o *ReceiptAdjustment) GetItemNameOk() (*string, bool)`

GetItemNameOk returns a tuple with the ItemName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemName

`func (o *ReceiptAdjustment) SetItemName(v string)`

SetItemName sets ItemName field to given value.

### HasItemName

`func (o *ReceiptAdjustment) HasItemName() bool`

HasItemName returns a boolean if a field has been set.

### SetItemNameNil

`func (o *ReceiptAdjustment) SetItemNameNil(b bool)`

 SetItemNameNil sets the value for ItemName to be an explicit nil

### UnsetItemName
`func (o *ReceiptAdjustment) UnsetItemName()`

UnsetItemName ensures that no value is present for ItemName, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


