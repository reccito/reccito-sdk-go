# OfferPolicyInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OfferText** | **string** |  | 
**OfferEndDate** | Pointer to **NullableTime** |  | [optional] 
**Terms** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewOfferPolicyInfo

`func NewOfferPolicyInfo(offerText string, ) *OfferPolicyInfo`

NewOfferPolicyInfo instantiates a new OfferPolicyInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOfferPolicyInfoWithDefaults

`func NewOfferPolicyInfoWithDefaults() *OfferPolicyInfo`

NewOfferPolicyInfoWithDefaults instantiates a new OfferPolicyInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOfferText

`func (o *OfferPolicyInfo) GetOfferText() string`

GetOfferText returns the OfferText field if non-nil, zero value otherwise.

### GetOfferTextOk

`func (o *OfferPolicyInfo) GetOfferTextOk() (*string, bool)`

GetOfferTextOk returns a tuple with the OfferText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOfferText

`func (o *OfferPolicyInfo) SetOfferText(v string)`

SetOfferText sets OfferText field to given value.


### GetOfferEndDate

`func (o *OfferPolicyInfo) GetOfferEndDate() time.Time`

GetOfferEndDate returns the OfferEndDate field if non-nil, zero value otherwise.

### GetOfferEndDateOk

`func (o *OfferPolicyInfo) GetOfferEndDateOk() (*time.Time, bool)`

GetOfferEndDateOk returns a tuple with the OfferEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOfferEndDate

`func (o *OfferPolicyInfo) SetOfferEndDate(v time.Time)`

SetOfferEndDate sets OfferEndDate field to given value.

### HasOfferEndDate

`func (o *OfferPolicyInfo) HasOfferEndDate() bool`

HasOfferEndDate returns a boolean if a field has been set.

### SetOfferEndDateNil

`func (o *OfferPolicyInfo) SetOfferEndDateNil(b bool)`

 SetOfferEndDateNil sets the value for OfferEndDate to be an explicit nil

### UnsetOfferEndDate
`func (o *OfferPolicyInfo) UnsetOfferEndDate()`

UnsetOfferEndDate ensures that no value is present for OfferEndDate, not even an explicit nil
### GetTerms

`func (o *OfferPolicyInfo) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *OfferPolicyInfo) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *OfferPolicyInfo) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *OfferPolicyInfo) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### SetTermsNil

`func (o *OfferPolicyInfo) SetTermsNil(b bool)`

 SetTermsNil sets the value for Terms to be an explicit nil

### UnsetTerms
`func (o *OfferPolicyInfo) UnsetTerms()`

UnsetTerms ensures that no value is present for Terms, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


