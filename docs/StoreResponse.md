# StoreResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**Code** | **string** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**OrganisationId** | **string** |  | 
**AddressLine1** | Pointer to **NullableString** |  | [optional] 
**AddressLine2** | Pointer to **NullableString** |  | [optional] 
**City** | Pointer to **NullableString** |  | [optional] 
**State** | Pointer to **NullableString** |  | [optional] 
**PostalCode** | Pointer to **NullableString** |  | [optional] 
**Country** | **string** |  | 
**FullAddress** | **string** |  | 
**Latitude** | Pointer to **NullableString** |  | [optional] 
**Longitude** | Pointer to **NullableString** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**Email** | Pointer to **NullableString** |  | [optional] 
**ManagerName** | Pointer to **NullableString** |  | [optional] 
**Timezone** | Pointer to **NullableString** |  | [optional] 
**DefaultQrExpiryMinutes** | Pointer to **NullableInt32** |  | [optional] 
**EffectiveQrExpiry** | **int32** |  | 
**LogoUrl** | Pointer to **NullableString** |  | [optional] 
**PrimaryColor** | Pointer to **NullableString** |  | [optional] 
**EffectiveLogoUrl** | Pointer to **NullableString** |  | [optional] 
**EffectivePrimaryColor** | Pointer to **NullableString** |  | [optional] 
**IsActive** | **bool** |  | 
**OpeningHours** | Pointer to **map[string]interface{}** |  | [optional] 
**ReceiptsCreatedCount** | **int32** |  | 
**LastReceiptCreated** | Pointer to **NullableTime** |  | [optional] 
**CustomMetadata** | Pointer to **map[string]interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewStoreResponse

`func NewStoreResponse(id string, name string, code string, organisationId string, country string, fullAddress string, effectiveQrExpiry int32, isActive bool, receiptsCreatedCount int32, createdAt time.Time, updatedAt time.Time, ) *StoreResponse`

NewStoreResponse instantiates a new StoreResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreResponseWithDefaults

`func NewStoreResponseWithDefaults() *StoreResponse`

NewStoreResponseWithDefaults instantiates a new StoreResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *StoreResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StoreResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StoreResponse) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *StoreResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StoreResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StoreResponse) SetName(v string)`

SetName sets Name field to given value.


### GetCode

`func (o *StoreResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *StoreResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *StoreResponse) SetCode(v string)`

SetCode sets Code field to given value.


### GetDescription

`func (o *StoreResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *StoreResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *StoreResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *StoreResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *StoreResponse) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *StoreResponse) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetOrganisationId

`func (o *StoreResponse) GetOrganisationId() string`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *StoreResponse) GetOrganisationIdOk() (*string, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *StoreResponse) SetOrganisationId(v string)`

SetOrganisationId sets OrganisationId field to given value.


### GetAddressLine1

`func (o *StoreResponse) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *StoreResponse) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *StoreResponse) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *StoreResponse) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### SetAddressLine1Nil

`func (o *StoreResponse) SetAddressLine1Nil(b bool)`

 SetAddressLine1Nil sets the value for AddressLine1 to be an explicit nil

### UnsetAddressLine1
`func (o *StoreResponse) UnsetAddressLine1()`

UnsetAddressLine1 ensures that no value is present for AddressLine1, not even an explicit nil
### GetAddressLine2

`func (o *StoreResponse) GetAddressLine2() string`

GetAddressLine2 returns the AddressLine2 field if non-nil, zero value otherwise.

### GetAddressLine2Ok

`func (o *StoreResponse) GetAddressLine2Ok() (*string, bool)`

GetAddressLine2Ok returns a tuple with the AddressLine2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine2

`func (o *StoreResponse) SetAddressLine2(v string)`

SetAddressLine2 sets AddressLine2 field to given value.

### HasAddressLine2

`func (o *StoreResponse) HasAddressLine2() bool`

HasAddressLine2 returns a boolean if a field has been set.

### SetAddressLine2Nil

`func (o *StoreResponse) SetAddressLine2Nil(b bool)`

 SetAddressLine2Nil sets the value for AddressLine2 to be an explicit nil

### UnsetAddressLine2
`func (o *StoreResponse) UnsetAddressLine2()`

UnsetAddressLine2 ensures that no value is present for AddressLine2, not even an explicit nil
### GetCity

`func (o *StoreResponse) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *StoreResponse) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *StoreResponse) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *StoreResponse) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *StoreResponse) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *StoreResponse) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetState

`func (o *StoreResponse) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *StoreResponse) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *StoreResponse) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *StoreResponse) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *StoreResponse) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *StoreResponse) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetPostalCode

`func (o *StoreResponse) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *StoreResponse) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *StoreResponse) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.

### HasPostalCode

`func (o *StoreResponse) HasPostalCode() bool`

HasPostalCode returns a boolean if a field has been set.

### SetPostalCodeNil

`func (o *StoreResponse) SetPostalCodeNil(b bool)`

 SetPostalCodeNil sets the value for PostalCode to be an explicit nil

### UnsetPostalCode
`func (o *StoreResponse) UnsetPostalCode()`

UnsetPostalCode ensures that no value is present for PostalCode, not even an explicit nil
### GetCountry

`func (o *StoreResponse) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *StoreResponse) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *StoreResponse) SetCountry(v string)`

SetCountry sets Country field to given value.


### GetFullAddress

`func (o *StoreResponse) GetFullAddress() string`

GetFullAddress returns the FullAddress field if non-nil, zero value otherwise.

### GetFullAddressOk

`func (o *StoreResponse) GetFullAddressOk() (*string, bool)`

GetFullAddressOk returns a tuple with the FullAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullAddress

`func (o *StoreResponse) SetFullAddress(v string)`

SetFullAddress sets FullAddress field to given value.


### GetLatitude

`func (o *StoreResponse) GetLatitude() string`

GetLatitude returns the Latitude field if non-nil, zero value otherwise.

### GetLatitudeOk

`func (o *StoreResponse) GetLatitudeOk() (*string, bool)`

GetLatitudeOk returns a tuple with the Latitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatitude

`func (o *StoreResponse) SetLatitude(v string)`

SetLatitude sets Latitude field to given value.

### HasLatitude

`func (o *StoreResponse) HasLatitude() bool`

HasLatitude returns a boolean if a field has been set.

### SetLatitudeNil

`func (o *StoreResponse) SetLatitudeNil(b bool)`

 SetLatitudeNil sets the value for Latitude to be an explicit nil

### UnsetLatitude
`func (o *StoreResponse) UnsetLatitude()`

UnsetLatitude ensures that no value is present for Latitude, not even an explicit nil
### GetLongitude

`func (o *StoreResponse) GetLongitude() string`

GetLongitude returns the Longitude field if non-nil, zero value otherwise.

### GetLongitudeOk

`func (o *StoreResponse) GetLongitudeOk() (*string, bool)`

GetLongitudeOk returns a tuple with the Longitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongitude

`func (o *StoreResponse) SetLongitude(v string)`

SetLongitude sets Longitude field to given value.

### HasLongitude

`func (o *StoreResponse) HasLongitude() bool`

HasLongitude returns a boolean if a field has been set.

### SetLongitudeNil

`func (o *StoreResponse) SetLongitudeNil(b bool)`

 SetLongitudeNil sets the value for Longitude to be an explicit nil

### UnsetLongitude
`func (o *StoreResponse) UnsetLongitude()`

UnsetLongitude ensures that no value is present for Longitude, not even an explicit nil
### GetPhone

`func (o *StoreResponse) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *StoreResponse) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *StoreResponse) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *StoreResponse) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *StoreResponse) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *StoreResponse) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetEmail

`func (o *StoreResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *StoreResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *StoreResponse) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *StoreResponse) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *StoreResponse) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *StoreResponse) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetManagerName

`func (o *StoreResponse) GetManagerName() string`

GetManagerName returns the ManagerName field if non-nil, zero value otherwise.

### GetManagerNameOk

`func (o *StoreResponse) GetManagerNameOk() (*string, bool)`

GetManagerNameOk returns a tuple with the ManagerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagerName

`func (o *StoreResponse) SetManagerName(v string)`

SetManagerName sets ManagerName field to given value.

### HasManagerName

`func (o *StoreResponse) HasManagerName() bool`

HasManagerName returns a boolean if a field has been set.

### SetManagerNameNil

`func (o *StoreResponse) SetManagerNameNil(b bool)`

 SetManagerNameNil sets the value for ManagerName to be an explicit nil

### UnsetManagerName
`func (o *StoreResponse) UnsetManagerName()`

UnsetManagerName ensures that no value is present for ManagerName, not even an explicit nil
### GetTimezone

`func (o *StoreResponse) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *StoreResponse) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *StoreResponse) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *StoreResponse) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### SetTimezoneNil

`func (o *StoreResponse) SetTimezoneNil(b bool)`

 SetTimezoneNil sets the value for Timezone to be an explicit nil

### UnsetTimezone
`func (o *StoreResponse) UnsetTimezone()`

UnsetTimezone ensures that no value is present for Timezone, not even an explicit nil
### GetDefaultQrExpiryMinutes

`func (o *StoreResponse) GetDefaultQrExpiryMinutes() int32`

GetDefaultQrExpiryMinutes returns the DefaultQrExpiryMinutes field if non-nil, zero value otherwise.

### GetDefaultQrExpiryMinutesOk

`func (o *StoreResponse) GetDefaultQrExpiryMinutesOk() (*int32, bool)`

GetDefaultQrExpiryMinutesOk returns a tuple with the DefaultQrExpiryMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultQrExpiryMinutes

`func (o *StoreResponse) SetDefaultQrExpiryMinutes(v int32)`

SetDefaultQrExpiryMinutes sets DefaultQrExpiryMinutes field to given value.

### HasDefaultQrExpiryMinutes

`func (o *StoreResponse) HasDefaultQrExpiryMinutes() bool`

HasDefaultQrExpiryMinutes returns a boolean if a field has been set.

### SetDefaultQrExpiryMinutesNil

`func (o *StoreResponse) SetDefaultQrExpiryMinutesNil(b bool)`

 SetDefaultQrExpiryMinutesNil sets the value for DefaultQrExpiryMinutes to be an explicit nil

### UnsetDefaultQrExpiryMinutes
`func (o *StoreResponse) UnsetDefaultQrExpiryMinutes()`

UnsetDefaultQrExpiryMinutes ensures that no value is present for DefaultQrExpiryMinutes, not even an explicit nil
### GetEffectiveQrExpiry

`func (o *StoreResponse) GetEffectiveQrExpiry() int32`

GetEffectiveQrExpiry returns the EffectiveQrExpiry field if non-nil, zero value otherwise.

### GetEffectiveQrExpiryOk

`func (o *StoreResponse) GetEffectiveQrExpiryOk() (*int32, bool)`

GetEffectiveQrExpiryOk returns a tuple with the EffectiveQrExpiry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveQrExpiry

`func (o *StoreResponse) SetEffectiveQrExpiry(v int32)`

SetEffectiveQrExpiry sets EffectiveQrExpiry field to given value.


### GetLogoUrl

`func (o *StoreResponse) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *StoreResponse) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *StoreResponse) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.

### HasLogoUrl

`func (o *StoreResponse) HasLogoUrl() bool`

HasLogoUrl returns a boolean if a field has been set.

### SetLogoUrlNil

`func (o *StoreResponse) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *StoreResponse) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil
### GetPrimaryColor

`func (o *StoreResponse) GetPrimaryColor() string`

GetPrimaryColor returns the PrimaryColor field if non-nil, zero value otherwise.

### GetPrimaryColorOk

`func (o *StoreResponse) GetPrimaryColorOk() (*string, bool)`

GetPrimaryColorOk returns a tuple with the PrimaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryColor

`func (o *StoreResponse) SetPrimaryColor(v string)`

SetPrimaryColor sets PrimaryColor field to given value.

### HasPrimaryColor

`func (o *StoreResponse) HasPrimaryColor() bool`

HasPrimaryColor returns a boolean if a field has been set.

### SetPrimaryColorNil

`func (o *StoreResponse) SetPrimaryColorNil(b bool)`

 SetPrimaryColorNil sets the value for PrimaryColor to be an explicit nil

### UnsetPrimaryColor
`func (o *StoreResponse) UnsetPrimaryColor()`

UnsetPrimaryColor ensures that no value is present for PrimaryColor, not even an explicit nil
### GetEffectiveLogoUrl

`func (o *StoreResponse) GetEffectiveLogoUrl() string`

GetEffectiveLogoUrl returns the EffectiveLogoUrl field if non-nil, zero value otherwise.

### GetEffectiveLogoUrlOk

`func (o *StoreResponse) GetEffectiveLogoUrlOk() (*string, bool)`

GetEffectiveLogoUrlOk returns a tuple with the EffectiveLogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveLogoUrl

`func (o *StoreResponse) SetEffectiveLogoUrl(v string)`

SetEffectiveLogoUrl sets EffectiveLogoUrl field to given value.

### HasEffectiveLogoUrl

`func (o *StoreResponse) HasEffectiveLogoUrl() bool`

HasEffectiveLogoUrl returns a boolean if a field has been set.

### SetEffectiveLogoUrlNil

`func (o *StoreResponse) SetEffectiveLogoUrlNil(b bool)`

 SetEffectiveLogoUrlNil sets the value for EffectiveLogoUrl to be an explicit nil

### UnsetEffectiveLogoUrl
`func (o *StoreResponse) UnsetEffectiveLogoUrl()`

UnsetEffectiveLogoUrl ensures that no value is present for EffectiveLogoUrl, not even an explicit nil
### GetEffectivePrimaryColor

`func (o *StoreResponse) GetEffectivePrimaryColor() string`

GetEffectivePrimaryColor returns the EffectivePrimaryColor field if non-nil, zero value otherwise.

### GetEffectivePrimaryColorOk

`func (o *StoreResponse) GetEffectivePrimaryColorOk() (*string, bool)`

GetEffectivePrimaryColorOk returns a tuple with the EffectivePrimaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectivePrimaryColor

`func (o *StoreResponse) SetEffectivePrimaryColor(v string)`

SetEffectivePrimaryColor sets EffectivePrimaryColor field to given value.

### HasEffectivePrimaryColor

`func (o *StoreResponse) HasEffectivePrimaryColor() bool`

HasEffectivePrimaryColor returns a boolean if a field has been set.

### SetEffectivePrimaryColorNil

`func (o *StoreResponse) SetEffectivePrimaryColorNil(b bool)`

 SetEffectivePrimaryColorNil sets the value for EffectivePrimaryColor to be an explicit nil

### UnsetEffectivePrimaryColor
`func (o *StoreResponse) UnsetEffectivePrimaryColor()`

UnsetEffectivePrimaryColor ensures that no value is present for EffectivePrimaryColor, not even an explicit nil
### GetIsActive

`func (o *StoreResponse) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *StoreResponse) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *StoreResponse) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetOpeningHours

`func (o *StoreResponse) GetOpeningHours() map[string]interface{}`

GetOpeningHours returns the OpeningHours field if non-nil, zero value otherwise.

### GetOpeningHoursOk

`func (o *StoreResponse) GetOpeningHoursOk() (*map[string]interface{}, bool)`

GetOpeningHoursOk returns a tuple with the OpeningHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpeningHours

`func (o *StoreResponse) SetOpeningHours(v map[string]interface{})`

SetOpeningHours sets OpeningHours field to given value.

### HasOpeningHours

`func (o *StoreResponse) HasOpeningHours() bool`

HasOpeningHours returns a boolean if a field has been set.

### SetOpeningHoursNil

`func (o *StoreResponse) SetOpeningHoursNil(b bool)`

 SetOpeningHoursNil sets the value for OpeningHours to be an explicit nil

### UnsetOpeningHours
`func (o *StoreResponse) UnsetOpeningHours()`

UnsetOpeningHours ensures that no value is present for OpeningHours, not even an explicit nil
### GetReceiptsCreatedCount

`func (o *StoreResponse) GetReceiptsCreatedCount() int32`

GetReceiptsCreatedCount returns the ReceiptsCreatedCount field if non-nil, zero value otherwise.

### GetReceiptsCreatedCountOk

`func (o *StoreResponse) GetReceiptsCreatedCountOk() (*int32, bool)`

GetReceiptsCreatedCountOk returns a tuple with the ReceiptsCreatedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptsCreatedCount

`func (o *StoreResponse) SetReceiptsCreatedCount(v int32)`

SetReceiptsCreatedCount sets ReceiptsCreatedCount field to given value.


### GetLastReceiptCreated

`func (o *StoreResponse) GetLastReceiptCreated() time.Time`

GetLastReceiptCreated returns the LastReceiptCreated field if non-nil, zero value otherwise.

### GetLastReceiptCreatedOk

`func (o *StoreResponse) GetLastReceiptCreatedOk() (*time.Time, bool)`

GetLastReceiptCreatedOk returns a tuple with the LastReceiptCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastReceiptCreated

`func (o *StoreResponse) SetLastReceiptCreated(v time.Time)`

SetLastReceiptCreated sets LastReceiptCreated field to given value.

### HasLastReceiptCreated

`func (o *StoreResponse) HasLastReceiptCreated() bool`

HasLastReceiptCreated returns a boolean if a field has been set.

### SetLastReceiptCreatedNil

`func (o *StoreResponse) SetLastReceiptCreatedNil(b bool)`

 SetLastReceiptCreatedNil sets the value for LastReceiptCreated to be an explicit nil

### UnsetLastReceiptCreated
`func (o *StoreResponse) UnsetLastReceiptCreated()`

UnsetLastReceiptCreated ensures that no value is present for LastReceiptCreated, not even an explicit nil
### GetCustomMetadata

`func (o *StoreResponse) GetCustomMetadata() map[string]interface{}`

GetCustomMetadata returns the CustomMetadata field if non-nil, zero value otherwise.

### GetCustomMetadataOk

`func (o *StoreResponse) GetCustomMetadataOk() (*map[string]interface{}, bool)`

GetCustomMetadataOk returns a tuple with the CustomMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomMetadata

`func (o *StoreResponse) SetCustomMetadata(v map[string]interface{})`

SetCustomMetadata sets CustomMetadata field to given value.

### HasCustomMetadata

`func (o *StoreResponse) HasCustomMetadata() bool`

HasCustomMetadata returns a boolean if a field has been set.

### SetCustomMetadataNil

`func (o *StoreResponse) SetCustomMetadataNil(b bool)`

 SetCustomMetadataNil sets the value for CustomMetadata to be an explicit nil

### UnsetCustomMetadata
`func (o *StoreResponse) UnsetCustomMetadata()`

UnsetCustomMetadata ensures that no value is present for CustomMetadata, not even an explicit nil
### GetCreatedAt

`func (o *StoreResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *StoreResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *StoreResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *StoreResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *StoreResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *StoreResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


