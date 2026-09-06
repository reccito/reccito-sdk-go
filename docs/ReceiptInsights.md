# ReceiptInsights

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReturnWindowDays** | Pointer to **NullableInt32** |  | [optional] 
**ReturnDeadline** | Pointer to **NullableTime** |  | [optional] 
**RefundEligible** | Pointer to **NullableBool** |  | [optional] 
**WarrantyItems** | Pointer to [**[]WarrantyInfo**](WarrantyInfo.md) |  | [optional] 

## Methods

### NewReceiptInsights

`func NewReceiptInsights() *ReceiptInsights`

NewReceiptInsights instantiates a new ReceiptInsights object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptInsightsWithDefaults

`func NewReceiptInsightsWithDefaults() *ReceiptInsights`

NewReceiptInsightsWithDefaults instantiates a new ReceiptInsights object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReturnWindowDays

`func (o *ReceiptInsights) GetReturnWindowDays() int32`

GetReturnWindowDays returns the ReturnWindowDays field if non-nil, zero value otherwise.

### GetReturnWindowDaysOk

`func (o *ReceiptInsights) GetReturnWindowDaysOk() (*int32, bool)`

GetReturnWindowDaysOk returns a tuple with the ReturnWindowDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnWindowDays

`func (o *ReceiptInsights) SetReturnWindowDays(v int32)`

SetReturnWindowDays sets ReturnWindowDays field to given value.

### HasReturnWindowDays

`func (o *ReceiptInsights) HasReturnWindowDays() bool`

HasReturnWindowDays returns a boolean if a field has been set.

### SetReturnWindowDaysNil

`func (o *ReceiptInsights) SetReturnWindowDaysNil(b bool)`

 SetReturnWindowDaysNil sets the value for ReturnWindowDays to be an explicit nil

### UnsetReturnWindowDays
`func (o *ReceiptInsights) UnsetReturnWindowDays()`

UnsetReturnWindowDays ensures that no value is present for ReturnWindowDays, not even an explicit nil
### GetReturnDeadline

`func (o *ReceiptInsights) GetReturnDeadline() time.Time`

GetReturnDeadline returns the ReturnDeadline field if non-nil, zero value otherwise.

### GetReturnDeadlineOk

`func (o *ReceiptInsights) GetReturnDeadlineOk() (*time.Time, bool)`

GetReturnDeadlineOk returns a tuple with the ReturnDeadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnDeadline

`func (o *ReceiptInsights) SetReturnDeadline(v time.Time)`

SetReturnDeadline sets ReturnDeadline field to given value.

### HasReturnDeadline

`func (o *ReceiptInsights) HasReturnDeadline() bool`

HasReturnDeadline returns a boolean if a field has been set.

### SetReturnDeadlineNil

`func (o *ReceiptInsights) SetReturnDeadlineNil(b bool)`

 SetReturnDeadlineNil sets the value for ReturnDeadline to be an explicit nil

### UnsetReturnDeadline
`func (o *ReceiptInsights) UnsetReturnDeadline()`

UnsetReturnDeadline ensures that no value is present for ReturnDeadline, not even an explicit nil
### GetRefundEligible

`func (o *ReceiptInsights) GetRefundEligible() bool`

GetRefundEligible returns the RefundEligible field if non-nil, zero value otherwise.

### GetRefundEligibleOk

`func (o *ReceiptInsights) GetRefundEligibleOk() (*bool, bool)`

GetRefundEligibleOk returns a tuple with the RefundEligible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundEligible

`func (o *ReceiptInsights) SetRefundEligible(v bool)`

SetRefundEligible sets RefundEligible field to given value.

### HasRefundEligible

`func (o *ReceiptInsights) HasRefundEligible() bool`

HasRefundEligible returns a boolean if a field has been set.

### SetRefundEligibleNil

`func (o *ReceiptInsights) SetRefundEligibleNil(b bool)`

 SetRefundEligibleNil sets the value for RefundEligible to be an explicit nil

### UnsetRefundEligible
`func (o *ReceiptInsights) UnsetRefundEligible()`

UnsetRefundEligible ensures that no value is present for RefundEligible, not even an explicit nil
### GetWarrantyItems

`func (o *ReceiptInsights) GetWarrantyItems() []WarrantyInfo`

GetWarrantyItems returns the WarrantyItems field if non-nil, zero value otherwise.

### GetWarrantyItemsOk

`func (o *ReceiptInsights) GetWarrantyItemsOk() (*[]WarrantyInfo, bool)`

GetWarrantyItemsOk returns a tuple with the WarrantyItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarrantyItems

`func (o *ReceiptInsights) SetWarrantyItems(v []WarrantyInfo)`

SetWarrantyItems sets WarrantyItems field to given value.

### HasWarrantyItems

`func (o *ReceiptInsights) HasWarrantyItems() bool`

HasWarrantyItems returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


