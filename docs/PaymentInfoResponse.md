# PaymentInfoResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Method** | **string** |  | 
**Amount** | **string** |  | 
**CardLastFour** | Pointer to **NullableString** |  | [optional] 
**Reference** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewPaymentInfoResponse

`func NewPaymentInfoResponse(method string, amount string, ) *PaymentInfoResponse`

NewPaymentInfoResponse instantiates a new PaymentInfoResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaymentInfoResponseWithDefaults

`func NewPaymentInfoResponseWithDefaults() *PaymentInfoResponse`

NewPaymentInfoResponseWithDefaults instantiates a new PaymentInfoResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMethod

`func (o *PaymentInfoResponse) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *PaymentInfoResponse) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *PaymentInfoResponse) SetMethod(v string)`

SetMethod sets Method field to given value.


### GetAmount

`func (o *PaymentInfoResponse) GetAmount() string`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *PaymentInfoResponse) GetAmountOk() (*string, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *PaymentInfoResponse) SetAmount(v string)`

SetAmount sets Amount field to given value.


### GetCardLastFour

`func (o *PaymentInfoResponse) GetCardLastFour() string`

GetCardLastFour returns the CardLastFour field if non-nil, zero value otherwise.

### GetCardLastFourOk

`func (o *PaymentInfoResponse) GetCardLastFourOk() (*string, bool)`

GetCardLastFourOk returns a tuple with the CardLastFour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardLastFour

`func (o *PaymentInfoResponse) SetCardLastFour(v string)`

SetCardLastFour sets CardLastFour field to given value.

### HasCardLastFour

`func (o *PaymentInfoResponse) HasCardLastFour() bool`

HasCardLastFour returns a boolean if a field has been set.

### SetCardLastFourNil

`func (o *PaymentInfoResponse) SetCardLastFourNil(b bool)`

 SetCardLastFourNil sets the value for CardLastFour to be an explicit nil

### UnsetCardLastFour
`func (o *PaymentInfoResponse) UnsetCardLastFour()`

UnsetCardLastFour ensures that no value is present for CardLastFour, not even an explicit nil
### GetReference

`func (o *PaymentInfoResponse) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *PaymentInfoResponse) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *PaymentInfoResponse) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *PaymentInfoResponse) HasReference() bool`

HasReference returns a boolean if a field has been set.

### SetReferenceNil

`func (o *PaymentInfoResponse) SetReferenceNil(b bool)`

 SetReferenceNil sets the value for Reference to be an explicit nil

### UnsetReference
`func (o *PaymentInfoResponse) UnsetReference()`

UnsetReference ensures that no value is present for Reference, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


