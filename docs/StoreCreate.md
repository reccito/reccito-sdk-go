# StoreCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Code** | **string** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**AddressLine1** | Pointer to **NullableString** |  | [optional] 
**AddressLine2** | Pointer to **NullableString** |  | [optional] 
**City** | Pointer to **NullableString** |  | [optional] 
**State** | Pointer to **NullableString** |  | [optional] 
**PostalCode** | Pointer to **NullableString** |  | [optional] 
**Country** | Pointer to **string** |  | [optional] [default to "US"]
**Latitude** | Pointer to **NullableString** |  | [optional] 
**Longitude** | Pointer to **NullableString** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**Email** | Pointer to **NullableString** |  | [optional] 
**ManagerName** | Pointer to **NullableString** |  | [optional] 
**Timezone** | Pointer to **NullableString** |  | [optional] 
**DefaultQrExpiryMinutes** | Pointer to **NullableInt32** |  | [optional] 
**LogoUrl** | Pointer to **NullableString** |  | [optional] 
**PrimaryColor** | Pointer to **NullableString** |  | [optional] 
**OpeningHours** | Pointer to **map[string]interface{}** |  | [optional] 
**CustomMetadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewStoreCreate

`func NewStoreCreate(name string, code string, ) *StoreCreate`

NewStoreCreate instantiates a new StoreCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreCreateWithDefaults

`func NewStoreCreateWithDefaults() *StoreCreate`

NewStoreCreateWithDefaults instantiates a new StoreCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *StoreCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StoreCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StoreCreate) SetName(v string)`

SetName sets Name field to given value.


### GetCode

`func (o *StoreCreate) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *StoreCreate) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *StoreCreate) SetCode(v string)`

SetCode sets Code field to given value.


### GetDescription

`func (o *StoreCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *StoreCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *StoreCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *StoreCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *StoreCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *StoreCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetAddressLine1

`func (o *StoreCreate) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *StoreCreate) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *StoreCreate) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *StoreCreate) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### SetAddressLine1Nil

`func (o *StoreCreate) SetAddressLine1Nil(b bool)`

 SetAddressLine1Nil sets the value for AddressLine1 to be an explicit nil

### UnsetAddressLine1
`func (o *StoreCreate) UnsetAddressLine1()`

UnsetAddressLine1 ensures that no value is present for AddressLine1, not even an explicit nil
### GetAddressLine2

`func (o *StoreCreate) GetAddressLine2() string`

GetAddressLine2 returns the AddressLine2 field if non-nil, zero value otherwise.

### GetAddressLine2Ok

`func (o *StoreCreate) GetAddressLine2Ok() (*string, bool)`

GetAddressLine2Ok returns a tuple with the AddressLine2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine2

`func (o *StoreCreate) SetAddressLine2(v string)`

SetAddressLine2 sets AddressLine2 field to given value.

### HasAddressLine2

`func (o *StoreCreate) HasAddressLine2() bool`

HasAddressLine2 returns a boolean if a field has been set.

### SetAddressLine2Nil

`func (o *StoreCreate) SetAddressLine2Nil(b bool)`

 SetAddressLine2Nil sets the value for AddressLine2 to be an explicit nil

### UnsetAddressLine2
`func (o *StoreCreate) UnsetAddressLine2()`

UnsetAddressLine2 ensures that no value is present for AddressLine2, not even an explicit nil
### GetCity

`func (o *StoreCreate) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *StoreCreate) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *StoreCreate) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *StoreCreate) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *StoreCreate) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *StoreCreate) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetState

`func (o *StoreCreate) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *StoreCreate) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *StoreCreate) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *StoreCreate) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *StoreCreate) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *StoreCreate) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetPostalCode

`func (o *StoreCreate) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *StoreCreate) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *StoreCreate) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.

### HasPostalCode

`func (o *StoreCreate) HasPostalCode() bool`

HasPostalCode returns a boolean if a field has been set.

### SetPostalCodeNil

`func (o *StoreCreate) SetPostalCodeNil(b bool)`

 SetPostalCodeNil sets the value for PostalCode to be an explicit nil

### UnsetPostalCode
`func (o *StoreCreate) UnsetPostalCode()`

UnsetPostalCode ensures that no value is present for PostalCode, not even an explicit nil
### GetCountry

`func (o *StoreCreate) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *StoreCreate) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *StoreCreate) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *StoreCreate) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetLatitude

`func (o *StoreCreate) GetLatitude() string`

GetLatitude returns the Latitude field if non-nil, zero value otherwise.

### GetLatitudeOk

`func (o *StoreCreate) GetLatitudeOk() (*string, bool)`

GetLatitudeOk returns a tuple with the Latitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatitude

`func (o *StoreCreate) SetLatitude(v string)`

SetLatitude sets Latitude field to given value.

### HasLatitude

`func (o *StoreCreate) HasLatitude() bool`

HasLatitude returns a boolean if a field has been set.

### SetLatitudeNil

`func (o *StoreCreate) SetLatitudeNil(b bool)`

 SetLatitudeNil sets the value for Latitude to be an explicit nil

### UnsetLatitude
`func (o *StoreCreate) UnsetLatitude()`

UnsetLatitude ensures that no value is present for Latitude, not even an explicit nil
### GetLongitude

`func (o *StoreCreate) GetLongitude() string`

GetLongitude returns the Longitude field if non-nil, zero value otherwise.

### GetLongitudeOk

`func (o *StoreCreate) GetLongitudeOk() (*string, bool)`

GetLongitudeOk returns a tuple with the Longitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongitude

`func (o *StoreCreate) SetLongitude(v string)`

SetLongitude sets Longitude field to given value.

### HasLongitude

`func (o *StoreCreate) HasLongitude() bool`

HasLongitude returns a boolean if a field has been set.

### SetLongitudeNil

`func (o *StoreCreate) SetLongitudeNil(b bool)`

 SetLongitudeNil sets the value for Longitude to be an explicit nil

### UnsetLongitude
`func (o *StoreCreate) UnsetLongitude()`

UnsetLongitude ensures that no value is present for Longitude, not even an explicit nil
### GetPhone

`func (o *StoreCreate) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *StoreCreate) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *StoreCreate) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *StoreCreate) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *StoreCreate) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *StoreCreate) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetEmail

`func (o *StoreCreate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *StoreCreate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *StoreCreate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *StoreCreate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *StoreCreate) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *StoreCreate) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetManagerName

`func (o *StoreCreate) GetManagerName() string`

GetManagerName returns the ManagerName field if non-nil, zero value otherwise.

### GetManagerNameOk

`func (o *StoreCreate) GetManagerNameOk() (*string, bool)`

GetManagerNameOk returns a tuple with the ManagerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagerName

`func (o *StoreCreate) SetManagerName(v string)`

SetManagerName sets ManagerName field to given value.

### HasManagerName

`func (o *StoreCreate) HasManagerName() bool`

HasManagerName returns a boolean if a field has been set.

### SetManagerNameNil

`func (o *StoreCreate) SetManagerNameNil(b bool)`

 SetManagerNameNil sets the value for ManagerName to be an explicit nil

### UnsetManagerName
`func (o *StoreCreate) UnsetManagerName()`

UnsetManagerName ensures that no value is present for ManagerName, not even an explicit nil
### GetTimezone

`func (o *StoreCreate) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *StoreCreate) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *StoreCreate) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *StoreCreate) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### SetTimezoneNil

`func (o *StoreCreate) SetTimezoneNil(b bool)`

 SetTimezoneNil sets the value for Timezone to be an explicit nil

### UnsetTimezone
`func (o *StoreCreate) UnsetTimezone()`

UnsetTimezone ensures that no value is present for Timezone, not even an explicit nil
### GetDefaultQrExpiryMinutes

`func (o *StoreCreate) GetDefaultQrExpiryMinutes() int32`

GetDefaultQrExpiryMinutes returns the DefaultQrExpiryMinutes field if non-nil, zero value otherwise.

### GetDefaultQrExpiryMinutesOk

`func (o *StoreCreate) GetDefaultQrExpiryMinutesOk() (*int32, bool)`

GetDefaultQrExpiryMinutesOk returns a tuple with the DefaultQrExpiryMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultQrExpiryMinutes

`func (o *StoreCreate) SetDefaultQrExpiryMinutes(v int32)`

SetDefaultQrExpiryMinutes sets DefaultQrExpiryMinutes field to given value.

### HasDefaultQrExpiryMinutes

`func (o *StoreCreate) HasDefaultQrExpiryMinutes() bool`

HasDefaultQrExpiryMinutes returns a boolean if a field has been set.

### SetDefaultQrExpiryMinutesNil

`func (o *StoreCreate) SetDefaultQrExpiryMinutesNil(b bool)`

 SetDefaultQrExpiryMinutesNil sets the value for DefaultQrExpiryMinutes to be an explicit nil

### UnsetDefaultQrExpiryMinutes
`func (o *StoreCreate) UnsetDefaultQrExpiryMinutes()`

UnsetDefaultQrExpiryMinutes ensures that no value is present for DefaultQrExpiryMinutes, not even an explicit nil
### GetLogoUrl

`func (o *StoreCreate) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *StoreCreate) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *StoreCreate) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.

### HasLogoUrl

`func (o *StoreCreate) HasLogoUrl() bool`

HasLogoUrl returns a boolean if a field has been set.

### SetLogoUrlNil

`func (o *StoreCreate) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *StoreCreate) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil
### GetPrimaryColor

`func (o *StoreCreate) GetPrimaryColor() string`

GetPrimaryColor returns the PrimaryColor field if non-nil, zero value otherwise.

### GetPrimaryColorOk

`func (o *StoreCreate) GetPrimaryColorOk() (*string, bool)`

GetPrimaryColorOk returns a tuple with the PrimaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryColor

`func (o *StoreCreate) SetPrimaryColor(v string)`

SetPrimaryColor sets PrimaryColor field to given value.

### HasPrimaryColor

`func (o *StoreCreate) HasPrimaryColor() bool`

HasPrimaryColor returns a boolean if a field has been set.

### SetPrimaryColorNil

`func (o *StoreCreate) SetPrimaryColorNil(b bool)`

 SetPrimaryColorNil sets the value for PrimaryColor to be an explicit nil

### UnsetPrimaryColor
`func (o *StoreCreate) UnsetPrimaryColor()`

UnsetPrimaryColor ensures that no value is present for PrimaryColor, not even an explicit nil
### GetOpeningHours

`func (o *StoreCreate) GetOpeningHours() map[string]interface{}`

GetOpeningHours returns the OpeningHours field if non-nil, zero value otherwise.

### GetOpeningHoursOk

`func (o *StoreCreate) GetOpeningHoursOk() (*map[string]interface{}, bool)`

GetOpeningHoursOk returns a tuple with the OpeningHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpeningHours

`func (o *StoreCreate) SetOpeningHours(v map[string]interface{})`

SetOpeningHours sets OpeningHours field to given value.

### HasOpeningHours

`func (o *StoreCreate) HasOpeningHours() bool`

HasOpeningHours returns a boolean if a field has been set.

### SetOpeningHoursNil

`func (o *StoreCreate) SetOpeningHoursNil(b bool)`

 SetOpeningHoursNil sets the value for OpeningHours to be an explicit nil

### UnsetOpeningHours
`func (o *StoreCreate) UnsetOpeningHours()`

UnsetOpeningHours ensures that no value is present for OpeningHours, not even an explicit nil
### GetCustomMetadata

`func (o *StoreCreate) GetCustomMetadata() map[string]interface{}`

GetCustomMetadata returns the CustomMetadata field if non-nil, zero value otherwise.

### GetCustomMetadataOk

`func (o *StoreCreate) GetCustomMetadataOk() (*map[string]interface{}, bool)`

GetCustomMetadataOk returns a tuple with the CustomMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomMetadata

`func (o *StoreCreate) SetCustomMetadata(v map[string]interface{})`

SetCustomMetadata sets CustomMetadata field to given value.

### HasCustomMetadata

`func (o *StoreCreate) HasCustomMetadata() bool`

HasCustomMetadata returns a boolean if a field has been set.

### SetCustomMetadataNil

`func (o *StoreCreate) SetCustomMetadataNil(b bool)`

 SetCustomMetadataNil sets the value for CustomMetadata to be an explicit nil

### UnsetCustomMetadata
`func (o *StoreCreate) UnsetCustomMetadata()`

UnsetCustomMetadata ensures that no value is present for CustomMetadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


