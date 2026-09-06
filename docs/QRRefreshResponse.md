# QRRefreshResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReceiptId** | **string** |  | 
**NewQrToken** | **string** |  | 
**NewQrCodeUrl** | **string** |  | 
**ExpiresAt** | **time.Time** |  | 

## Methods

### NewQRRefreshResponse

`func NewQRRefreshResponse(receiptId string, newQrToken string, newQrCodeUrl string, expiresAt time.Time, ) *QRRefreshResponse`

NewQRRefreshResponse instantiates a new QRRefreshResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQRRefreshResponseWithDefaults

`func NewQRRefreshResponseWithDefaults() *QRRefreshResponse`

NewQRRefreshResponseWithDefaults instantiates a new QRRefreshResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReceiptId

`func (o *QRRefreshResponse) GetReceiptId() string`

GetReceiptId returns the ReceiptId field if non-nil, zero value otherwise.

### GetReceiptIdOk

`func (o *QRRefreshResponse) GetReceiptIdOk() (*string, bool)`

GetReceiptIdOk returns a tuple with the ReceiptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptId

`func (o *QRRefreshResponse) SetReceiptId(v string)`

SetReceiptId sets ReceiptId field to given value.


### GetNewQrToken

`func (o *QRRefreshResponse) GetNewQrToken() string`

GetNewQrToken returns the NewQrToken field if non-nil, zero value otherwise.

### GetNewQrTokenOk

`func (o *QRRefreshResponse) GetNewQrTokenOk() (*string, bool)`

GetNewQrTokenOk returns a tuple with the NewQrToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewQrToken

`func (o *QRRefreshResponse) SetNewQrToken(v string)`

SetNewQrToken sets NewQrToken field to given value.


### GetNewQrCodeUrl

`func (o *QRRefreshResponse) GetNewQrCodeUrl() string`

GetNewQrCodeUrl returns the NewQrCodeUrl field if non-nil, zero value otherwise.

### GetNewQrCodeUrlOk

`func (o *QRRefreshResponse) GetNewQrCodeUrlOk() (*string, bool)`

GetNewQrCodeUrlOk returns a tuple with the NewQrCodeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewQrCodeUrl

`func (o *QRRefreshResponse) SetNewQrCodeUrl(v string)`

SetNewQrCodeUrl sets NewQrCodeUrl field to given value.


### GetExpiresAt

`func (o *QRRefreshResponse) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *QRRefreshResponse) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *QRRefreshResponse) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


