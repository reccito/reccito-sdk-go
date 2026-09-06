# Barcode

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Format** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewBarcode

`func NewBarcode(code string, ) *Barcode`

NewBarcode instantiates a new Barcode object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBarcodeWithDefaults

`func NewBarcodeWithDefaults() *Barcode`

NewBarcodeWithDefaults instantiates a new Barcode object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *Barcode) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *Barcode) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *Barcode) SetCode(v string)`

SetCode sets Code field to given value.


### GetFormat

`func (o *Barcode) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *Barcode) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *Barcode) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *Barcode) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### SetFormatNil

`func (o *Barcode) SetFormatNil(b bool)`

 SetFormatNil sets the value for Format to be an explicit nil

### UnsetFormat
`func (o *Barcode) UnsetFormat()`

UnsetFormat ensures that no value is present for Format, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


