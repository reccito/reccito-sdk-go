# PaymentInfoCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Method** | **string** |  | 
**Amount** | **string** |  | 
**CardLastFour** | Pointer to **NullableString** |  | [optional] 
**Reference** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewPaymentInfoCreate

`func NewPaymentInfoCreate(method string, amount string, ) *PaymentInfoCreate`

NewPaymentInfoCreate instantiates a new PaymentInfoCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaymentInfoCreateWithDefaults

`func NewPaymentInfoCreateWithDefaults() *PaymentInfoCreate`

NewPaymentInfoCreateWithDefaults instantiates a new PaymentInfoCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMethod

`func (o *PaymentInfoCreate) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *PaymentInfoCreate) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *PaymentInfoCreate) SetMethod(v string)`

SetMethod sets Method field to given value.


### GetAmount

`func (o *PaymentInfoCreate) GetAmount() string`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *PaymentInfoCreate) GetAmountOk() (*string, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *PaymentInfoCreate) SetAmount(v string)`

SetAmount sets Amount field to given value.


### GetCardLastFour

`func (o *PaymentInfoCreate) GetCardLastFour() string`

GetCardLastFour returns the CardLastFour field if non-nil, zero value otherwise.

### GetCardLastFourOk

`func (o *PaymentInfoCreate) GetCardLastFourOk() (*string, bool)`

GetCardLastFourOk returns a tuple with the CardLastFour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardLastFour

`func (o *PaymentInfoCreate) SetCardLastFour(v string)`

SetCardLastFour sets CardLastFour field to given value.

### HasCardLastFour

`func (o *PaymentInfoCreate) HasCardLastFour() bool`

HasCardLastFour returns a boolean if a field has been set.

### SetCardLastFourNil

`func (o *PaymentInfoCreate) SetCardLastFourNil(b bool)`

 SetCardLastFourNil sets the value for CardLastFour to be an explicit nil

### UnsetCardLastFour
`func (o *PaymentInfoCreate) UnsetCardLastFour()`

UnsetCardLastFour ensures that no value is present for CardLastFour, not even an explicit nil
### GetReference

`func (o *PaymentInfoCreate) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *PaymentInfoCreate) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *PaymentInfoCreate) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *PaymentInfoCreate) HasReference() bool`

HasReference returns a boolean if a field has been set.

### SetReferenceNil

`func (o *PaymentInfoCreate) SetReferenceNil(b bool)`

 SetReferenceNil sets the value for Reference to be an explicit nil

### UnsetReference
`func (o *PaymentInfoCreate) UnsetReference()`

UnsetReference ensures that no value is present for Reference, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


