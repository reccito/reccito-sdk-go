# StoreUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**AddressLine1** | Pointer to **NullableString** |  | [optional] 
**AddressLine2** | Pointer to **NullableString** |  | [optional] 
**City** | Pointer to **NullableString** |  | [optional] 
**State** | Pointer to **NullableString** |  | [optional] 
**PostalCode** | Pointer to **NullableString** |  | [optional] 
**Country** | Pointer to **NullableString** |  | [optional] 
**Latitude** | Pointer to **NullableString** |  | [optional] 
**Longitude** | Pointer to **NullableString** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**Email** | Pointer to **NullableString** |  | [optional] 
**ManagerName** | Pointer to **NullableString** |  | [optional] 
**Timezone** | Pointer to **NullableString** |  | [optional] 
**DefaultQrExpiryMinutes** | Pointer to **NullableInt32** |  | [optional] 
**LogoUrl** | Pointer to **NullableString** |  | [optional] 
**PrimaryColor** | Pointer to **NullableString** |  | [optional] 
**IsActive** | Pointer to **NullableBool** |  | [optional] 
**OpeningHours** | Pointer to **map[string]interface{}** |  | [optional] 
**CustomMetadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewStoreUpdate

`func NewStoreUpdate() *StoreUpdate`

NewStoreUpdate instantiates a new StoreUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreUpdateWithDefaults

`func NewStoreUpdateWithDefaults() *StoreUpdate`

NewStoreUpdateWithDefaults instantiates a new StoreUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *StoreUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StoreUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StoreUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *StoreUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *StoreUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *StoreUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDescription

`func (o *StoreUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *StoreUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *StoreUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *StoreUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *StoreUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *StoreUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetAddressLine1

`func (o *StoreUpdate) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *StoreUpdate) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *StoreUpdate) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *StoreUpdate) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### SetAddressLine1Nil

`func (o *StoreUpdate) SetAddressLine1Nil(b bool)`

 SetAddressLine1Nil sets the value for AddressLine1 to be an explicit nil

### UnsetAddressLine1
`func (o *StoreUpdate) UnsetAddressLine1()`

UnsetAddressLine1 ensures that no value is present for AddressLine1, not even an explicit nil
### GetAddressLine2

`func (o *StoreUpdate) GetAddressLine2() string`

GetAddressLine2 returns the AddressLine2 field if non-nil, zero value otherwise.

### GetAddressLine2Ok

`func (o *StoreUpdate) GetAddressLine2Ok() (*string, bool)`

GetAddressLine2Ok returns a tuple with the AddressLine2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine2

`func (o *StoreUpdate) SetAddressLine2(v string)`

SetAddressLine2 sets AddressLine2 field to given value.

### HasAddressLine2

`func (o *StoreUpdate) HasAddressLine2() bool`

HasAddressLine2 returns a boolean if a field has been set.

### SetAddressLine2Nil

`func (o *StoreUpdate) SetAddressLine2Nil(b bool)`

 SetAddressLine2Nil sets the value for AddressLine2 to be an explicit nil

### UnsetAddressLine2
`func (o *StoreUpdate) UnsetAddressLine2()`

UnsetAddressLine2 ensures that no value is present for AddressLine2, not even an explicit nil
### GetCity

`func (o *StoreUpdate) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *StoreUpdate) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *StoreUpdate) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *StoreUpdate) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *StoreUpdate) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *StoreUpdate) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetState

`func (o *StoreUpdate) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *StoreUpdate) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *StoreUpdate) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *StoreUpdate) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *StoreUpdate) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *StoreUpdate) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetPostalCode

`func (o *StoreUpdate) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *StoreUpdate) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *StoreUpdate) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.

### HasPostalCode

`func (o *StoreUpdate) HasPostalCode() bool`

HasPostalCode returns a boolean if a field has been set.

### SetPostalCodeNil

`func (o *StoreUpdate) SetPostalCodeNil(b bool)`

 SetPostalCodeNil sets the value for PostalCode to be an explicit nil

### UnsetPostalCode
`func (o *StoreUpdate) UnsetPostalCode()`

UnsetPostalCode ensures that no value is present for PostalCode, not even an explicit nil
### GetCountry

`func (o *StoreUpdate) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *StoreUpdate) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *StoreUpdate) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *StoreUpdate) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *StoreUpdate) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *StoreUpdate) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetLatitude

`func (o *StoreUpdate) GetLatitude() string`

GetLatitude returns the Latitude field if non-nil, zero value otherwise.

### GetLatitudeOk

`func (o *StoreUpdate) GetLatitudeOk() (*string, bool)`

GetLatitudeOk returns a tuple with the Latitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatitude

`func (o *StoreUpdate) SetLatitude(v string)`

SetLatitude sets Latitude field to given value.

### HasLatitude

`func (o *StoreUpdate) HasLatitude() bool`

HasLatitude returns a boolean if a field has been set.

### SetLatitudeNil

`func (o *StoreUpdate) SetLatitudeNil(b bool)`

 SetLatitudeNil sets the value for Latitude to be an explicit nil

### UnsetLatitude
`func (o *StoreUpdate) UnsetLatitude()`

UnsetLatitude ensures that no value is present for Latitude, not even an explicit nil
### GetLongitude

`func (o *StoreUpdate) GetLongitude() string`

GetLongitude returns the Longitude field if non-nil, zero value otherwise.

### GetLongitudeOk

`func (o *StoreUpdate) GetLongitudeOk() (*string, bool)`

GetLongitudeOk returns a tuple with the Longitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongitude

`func (o *StoreUpdate) SetLongitude(v string)`

SetLongitude sets Longitude field to given value.

### HasLongitude

`func (o *StoreUpdate) HasLongitude() bool`

HasLongitude returns a boolean if a field has been set.

### SetLongitudeNil

`func (o *StoreUpdate) SetLongitudeNil(b bool)`

 SetLongitudeNil sets the value for Longitude to be an explicit nil

### UnsetLongitude
`func (o *StoreUpdate) UnsetLongitude()`

UnsetLongitude ensures that no value is present for Longitude, not even an explicit nil
### GetPhone

`func (o *StoreUpdate) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *StoreUpdate) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *StoreUpdate) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *StoreUpdate) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *StoreUpdate) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *StoreUpdate) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetEmail

`func (o *StoreUpdate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *StoreUpdate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *StoreUpdate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *StoreUpdate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *StoreUpdate) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *StoreUpdate) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetManagerName

`func (o *StoreUpdate) GetManagerName() string`

GetManagerName returns the ManagerName field if non-nil, zero value otherwise.

### GetManagerNameOk

`func (o *StoreUpdate) GetManagerNameOk() (*string, bool)`

GetManagerNameOk returns a tuple with the ManagerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagerName

`func (o *StoreUpdate) SetManagerName(v string)`

SetManagerName sets ManagerName field to given value.

### HasManagerName

`func (o *StoreUpdate) HasManagerName() bool`

HasManagerName returns a boolean if a field has been set.

### SetManagerNameNil

`func (o *StoreUpdate) SetManagerNameNil(b bool)`

 SetManagerNameNil sets the value for ManagerName to be an explicit nil

### UnsetManagerName
`func (o *StoreUpdate) UnsetManagerName()`

UnsetManagerName ensures that no value is present for ManagerName, not even an explicit nil
### GetTimezone

`func (o *StoreUpdate) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *StoreUpdate) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *StoreUpdate) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *StoreUpdate) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### SetTimezoneNil

`func (o *StoreUpdate) SetTimezoneNil(b bool)`

 SetTimezoneNil sets the value for Timezone to be an explicit nil

### UnsetTimezone
`func (o *StoreUpdate) UnsetTimezone()`

UnsetTimezone ensures that no value is present for Timezone, not even an explicit nil
### GetDefaultQrExpiryMinutes

`func (o *StoreUpdate) GetDefaultQrExpiryMinutes() int32`

GetDefaultQrExpiryMinutes returns the DefaultQrExpiryMinutes field if non-nil, zero value otherwise.

### GetDefaultQrExpiryMinutesOk

`func (o *StoreUpdate) GetDefaultQrExpiryMinutesOk() (*int32, bool)`

GetDefaultQrExpiryMinutesOk returns a tuple with the DefaultQrExpiryMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultQrExpiryMinutes

`func (o *StoreUpdate) SetDefaultQrExpiryMinutes(v int32)`

SetDefaultQrExpiryMinutes sets DefaultQrExpiryMinutes field to given value.

### HasDefaultQrExpiryMinutes

`func (o *StoreUpdate) HasDefaultQrExpiryMinutes() bool`

HasDefaultQrExpiryMinutes returns a boolean if a field has been set.

### SetDefaultQrExpiryMinutesNil

`func (o *StoreUpdate) SetDefaultQrExpiryMinutesNil(b bool)`

 SetDefaultQrExpiryMinutesNil sets the value for DefaultQrExpiryMinutes to be an explicit nil

### UnsetDefaultQrExpiryMinutes
`func (o *StoreUpdate) UnsetDefaultQrExpiryMinutes()`

UnsetDefaultQrExpiryMinutes ensures that no value is present for DefaultQrExpiryMinutes, not even an explicit nil
### GetLogoUrl

`func (o *StoreUpdate) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *StoreUpdate) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *StoreUpdate) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.

### HasLogoUrl

`func (o *StoreUpdate) HasLogoUrl() bool`

HasLogoUrl returns a boolean if a field has been set.

### SetLogoUrlNil

`func (o *StoreUpdate) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *StoreUpdate) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil
### GetPrimaryColor

`func (o *StoreUpdate) GetPrimaryColor() string`

GetPrimaryColor returns the PrimaryColor field if non-nil, zero value otherwise.

### GetPrimaryColorOk

`func (o *StoreUpdate) GetPrimaryColorOk() (*string, bool)`

GetPrimaryColorOk returns a tuple with the PrimaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryColor

`func (o *StoreUpdate) SetPrimaryColor(v string)`

SetPrimaryColor sets PrimaryColor field to given value.

### HasPrimaryColor

`func (o *StoreUpdate) HasPrimaryColor() bool`

HasPrimaryColor returns a boolean if a field has been set.

### SetPrimaryColorNil

`func (o *StoreUpdate) SetPrimaryColorNil(b bool)`

 SetPrimaryColorNil sets the value for PrimaryColor to be an explicit nil

### UnsetPrimaryColor
`func (o *StoreUpdate) UnsetPrimaryColor()`

UnsetPrimaryColor ensures that no value is present for PrimaryColor, not even an explicit nil
### GetIsActive

`func (o *StoreUpdate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *StoreUpdate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *StoreUpdate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *StoreUpdate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *StoreUpdate) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *StoreUpdate) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetOpeningHours

`func (o *StoreUpdate) GetOpeningHours() map[string]interface{}`

GetOpeningHours returns the OpeningHours field if non-nil, zero value otherwise.

### GetOpeningHoursOk

`func (o *StoreUpdate) GetOpeningHoursOk() (*map[string]interface{}, bool)`

GetOpeningHoursOk returns a tuple with the OpeningHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpeningHours

`func (o *StoreUpdate) SetOpeningHours(v map[string]interface{})`

SetOpeningHours sets OpeningHours field to given value.

### HasOpeningHours

`func (o *StoreUpdate) HasOpeningHours() bool`

HasOpeningHours returns a boolean if a field has been set.

### SetOpeningHoursNil

`func (o *StoreUpdate) SetOpeningHoursNil(b bool)`

 SetOpeningHoursNil sets the value for OpeningHours to be an explicit nil

### UnsetOpeningHours
`func (o *StoreUpdate) UnsetOpeningHours()`

UnsetOpeningHours ensures that no value is present for OpeningHours, not even an explicit nil
### GetCustomMetadata

`func (o *StoreUpdate) GetCustomMetadata() map[string]interface{}`

GetCustomMetadata returns the CustomMetadata field if non-nil, zero value otherwise.

### GetCustomMetadataOk

`func (o *StoreUpdate) GetCustomMetadataOk() (*map[string]interface{}, bool)`

GetCustomMetadataOk returns a tuple with the CustomMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomMetadata

`func (o *StoreUpdate) SetCustomMetadata(v map[string]interface{})`

SetCustomMetadata sets CustomMetadata field to given value.

### HasCustomMetadata

`func (o *StoreUpdate) HasCustomMetadata() bool`

HasCustomMetadata returns a boolean if a field has been set.

### SetCustomMetadataNil

`func (o *StoreUpdate) SetCustomMetadataNil(b bool)`

 SetCustomMetadataNil sets the value for CustomMetadata to be an explicit nil

### UnsetCustomMetadata
`func (o *StoreUpdate) UnsetCustomMetadata()`

UnsetCustomMetadata ensures that no value is present for CustomMetadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


