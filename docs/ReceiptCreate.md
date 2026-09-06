# ReceiptCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MerchantReceiptId** | Pointer to **NullableString** |  | [optional] 
**DedupeKey** | Pointer to **NullableString** |  | [optional] 
**Barcode** | Pointer to [**NullableBarcode**](Barcode.md) |  | [optional] 
**StoreId** | Pointer to **NullableString** |  | [optional] 
**TransactionDate** | **time.Time** |  | 
**OrderNumber** | Pointer to **NullableString** |  | [optional] 
**Cashier** | Pointer to **NullableString** |  | [optional] 
**Items** | [**[]ReceiptItemCreate**](ReceiptItemCreate.md) |  | 
**Subtotal** | **string** |  | 
**TaxAmount** | **string** |  | 
**DiscountAmount** | Pointer to **string** |  | [optional] [default to "0"]
**TipAmount** | Pointer to **string** |  | [optional] [default to "0"]
**TotalAmount** | **string** |  | 
**Currency** | **string** |  | 
**PaymentInfo** | [**[]PaymentInfoCreate**](PaymentInfoCreate.md) |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**ReturnPolicy** | Pointer to **NullableString** |  | [optional] 
**Offers** | Pointer to **[]string** |  | [optional] 
**OfferPolicies** | Pointer to [**[]OfferPolicyInfo**](OfferPolicyInfo.md) |  | [optional] 
**FeedbackUrl** | Pointer to **NullableString** |  | [optional] 
**LoyaltyInfo** | Pointer to **NullableString** |  | [optional] 
**MerchantDetails** | Pointer to [**NullableMerchantDetails**](MerchantDetails.md) |  | [optional] 
**Adjustments** | Pointer to [**[]ReceiptAdjustment**](ReceiptAdjustment.md) |  | [optional] 
**TransactionReferences** | Pointer to [**[]TransactionReference**](TransactionReference.md) |  | [optional] 
**Warranties** | Pointer to [**[]WarrantyInfo**](WarrantyInfo.md) |  | [optional] 
**Insights** | Pointer to [**NullableReceiptInsights**](ReceiptInsights.md) |  | [optional] 
**ReturnInsights** | Pointer to [**NullableReturnInsights**](ReturnInsights.md) |  | [optional] 
**QrExpiryMinutes** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewReceiptCreate

`func NewReceiptCreate(transactionDate time.Time, items []ReceiptItemCreate, subtotal string, taxAmount string, totalAmount string, currency string, paymentInfo []PaymentInfoCreate, ) *ReceiptCreate`

NewReceiptCreate instantiates a new ReceiptCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptCreateWithDefaults

`func NewReceiptCreateWithDefaults() *ReceiptCreate`

NewReceiptCreateWithDefaults instantiates a new ReceiptCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMerchantReceiptId

`func (o *ReceiptCreate) GetMerchantReceiptId() string`

GetMerchantReceiptId returns the MerchantReceiptId field if non-nil, zero value otherwise.

### GetMerchantReceiptIdOk

`func (o *ReceiptCreate) GetMerchantReceiptIdOk() (*string, bool)`

GetMerchantReceiptIdOk returns a tuple with the MerchantReceiptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantReceiptId

`func (o *ReceiptCreate) SetMerchantReceiptId(v string)`

SetMerchantReceiptId sets MerchantReceiptId field to given value.

### HasMerchantReceiptId

`func (o *ReceiptCreate) HasMerchantReceiptId() bool`

HasMerchantReceiptId returns a boolean if a field has been set.

### SetMerchantReceiptIdNil

`func (o *ReceiptCreate) SetMerchantReceiptIdNil(b bool)`

 SetMerchantReceiptIdNil sets the value for MerchantReceiptId to be an explicit nil

### UnsetMerchantReceiptId
`func (o *ReceiptCreate) UnsetMerchantReceiptId()`

UnsetMerchantReceiptId ensures that no value is present for MerchantReceiptId, not even an explicit nil
### GetDedupeKey

`func (o *ReceiptCreate) GetDedupeKey() string`

GetDedupeKey returns the DedupeKey field if non-nil, zero value otherwise.

### GetDedupeKeyOk

`func (o *ReceiptCreate) GetDedupeKeyOk() (*string, bool)`

GetDedupeKeyOk returns a tuple with the DedupeKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDedupeKey

`func (o *ReceiptCreate) SetDedupeKey(v string)`

SetDedupeKey sets DedupeKey field to given value.

### HasDedupeKey

`func (o *ReceiptCreate) HasDedupeKey() bool`

HasDedupeKey returns a boolean if a field has been set.

### SetDedupeKeyNil

`func (o *ReceiptCreate) SetDedupeKeyNil(b bool)`

 SetDedupeKeyNil sets the value for DedupeKey to be an explicit nil

### UnsetDedupeKey
`func (o *ReceiptCreate) UnsetDedupeKey()`

UnsetDedupeKey ensures that no value is present for DedupeKey, not even an explicit nil
### GetBarcode

`func (o *ReceiptCreate) GetBarcode() Barcode`

GetBarcode returns the Barcode field if non-nil, zero value otherwise.

### GetBarcodeOk

`func (o *ReceiptCreate) GetBarcodeOk() (*Barcode, bool)`

GetBarcodeOk returns a tuple with the Barcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBarcode

`func (o *ReceiptCreate) SetBarcode(v Barcode)`

SetBarcode sets Barcode field to given value.

### HasBarcode

`func (o *ReceiptCreate) HasBarcode() bool`

HasBarcode returns a boolean if a field has been set.

### SetBarcodeNil

`func (o *ReceiptCreate) SetBarcodeNil(b bool)`

 SetBarcodeNil sets the value for Barcode to be an explicit nil

### UnsetBarcode
`func (o *ReceiptCreate) UnsetBarcode()`

UnsetBarcode ensures that no value is present for Barcode, not even an explicit nil
### GetStoreId

`func (o *ReceiptCreate) GetStoreId() string`

GetStoreId returns the StoreId field if non-nil, zero value otherwise.

### GetStoreIdOk

`func (o *ReceiptCreate) GetStoreIdOk() (*string, bool)`

GetStoreIdOk returns a tuple with the StoreId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreId

`func (o *ReceiptCreate) SetStoreId(v string)`

SetStoreId sets StoreId field to given value.

### HasStoreId

`func (o *ReceiptCreate) HasStoreId() bool`

HasStoreId returns a boolean if a field has been set.

### SetStoreIdNil

`func (o *ReceiptCreate) SetStoreIdNil(b bool)`

 SetStoreIdNil sets the value for StoreId to be an explicit nil

### UnsetStoreId
`func (o *ReceiptCreate) UnsetStoreId()`

UnsetStoreId ensures that no value is present for StoreId, not even an explicit nil
### GetTransactionDate

`func (o *ReceiptCreate) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *ReceiptCreate) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *ReceiptCreate) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.


### GetOrderNumber

`func (o *ReceiptCreate) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *ReceiptCreate) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *ReceiptCreate) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *ReceiptCreate) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### SetOrderNumberNil

`func (o *ReceiptCreate) SetOrderNumberNil(b bool)`

 SetOrderNumberNil sets the value for OrderNumber to be an explicit nil

### UnsetOrderNumber
`func (o *ReceiptCreate) UnsetOrderNumber()`

UnsetOrderNumber ensures that no value is present for OrderNumber, not even an explicit nil
### GetCashier

`func (o *ReceiptCreate) GetCashier() string`

GetCashier returns the Cashier field if non-nil, zero value otherwise.

### GetCashierOk

`func (o *ReceiptCreate) GetCashierOk() (*string, bool)`

GetCashierOk returns a tuple with the Cashier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCashier

`func (o *ReceiptCreate) SetCashier(v string)`

SetCashier sets Cashier field to given value.

### HasCashier

`func (o *ReceiptCreate) HasCashier() bool`

HasCashier returns a boolean if a field has been set.

### SetCashierNil

`func (o *ReceiptCreate) SetCashierNil(b bool)`

 SetCashierNil sets the value for Cashier to be an explicit nil

### UnsetCashier
`func (o *ReceiptCreate) UnsetCashier()`

UnsetCashier ensures that no value is present for Cashier, not even an explicit nil
### GetItems

`func (o *ReceiptCreate) GetItems() []ReceiptItemCreate`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ReceiptCreate) GetItemsOk() (*[]ReceiptItemCreate, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ReceiptCreate) SetItems(v []ReceiptItemCreate)`

SetItems sets Items field to given value.


### GetSubtotal

`func (o *ReceiptCreate) GetSubtotal() string`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *ReceiptCreate) GetSubtotalOk() (*string, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *ReceiptCreate) SetSubtotal(v string)`

SetSubtotal sets Subtotal field to given value.


### GetTaxAmount

`func (o *ReceiptCreate) GetTaxAmount() string`

GetTaxAmount returns the TaxAmount field if non-nil, zero value otherwise.

### GetTaxAmountOk

`func (o *ReceiptCreate) GetTaxAmountOk() (*string, bool)`

GetTaxAmountOk returns a tuple with the TaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmount

`func (o *ReceiptCreate) SetTaxAmount(v string)`

SetTaxAmount sets TaxAmount field to given value.


### GetDiscountAmount

`func (o *ReceiptCreate) GetDiscountAmount() string`

GetDiscountAmount returns the DiscountAmount field if non-nil, zero value otherwise.

### GetDiscountAmountOk

`func (o *ReceiptCreate) GetDiscountAmountOk() (*string, bool)`

GetDiscountAmountOk returns a tuple with the DiscountAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountAmount

`func (o *ReceiptCreate) SetDiscountAmount(v string)`

SetDiscountAmount sets DiscountAmount field to given value.

### HasDiscountAmount

`func (o *ReceiptCreate) HasDiscountAmount() bool`

HasDiscountAmount returns a boolean if a field has been set.

### GetTipAmount

`func (o *ReceiptCreate) GetTipAmount() string`

GetTipAmount returns the TipAmount field if non-nil, zero value otherwise.

### GetTipAmountOk

`func (o *ReceiptCreate) GetTipAmountOk() (*string, bool)`

GetTipAmountOk returns a tuple with the TipAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTipAmount

`func (o *ReceiptCreate) SetTipAmount(v string)`

SetTipAmount sets TipAmount field to given value.

### HasTipAmount

`func (o *ReceiptCreate) HasTipAmount() bool`

HasTipAmount returns a boolean if a field has been set.

### GetTotalAmount

`func (o *ReceiptCreate) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *ReceiptCreate) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *ReceiptCreate) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.


### GetCurrency

`func (o *ReceiptCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ReceiptCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ReceiptCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetPaymentInfo

`func (o *ReceiptCreate) GetPaymentInfo() []PaymentInfoCreate`

GetPaymentInfo returns the PaymentInfo field if non-nil, zero value otherwise.

### GetPaymentInfoOk

`func (o *ReceiptCreate) GetPaymentInfoOk() (*[]PaymentInfoCreate, bool)`

GetPaymentInfoOk returns a tuple with the PaymentInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentInfo

`func (o *ReceiptCreate) SetPaymentInfo(v []PaymentInfoCreate)`

SetPaymentInfo sets PaymentInfo field to given value.


### GetNotes

`func (o *ReceiptCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ReceiptCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ReceiptCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ReceiptCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ReceiptCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ReceiptCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetReturnPolicy

`func (o *ReceiptCreate) GetReturnPolicy() string`

GetReturnPolicy returns the ReturnPolicy field if non-nil, zero value otherwise.

### GetReturnPolicyOk

`func (o *ReceiptCreate) GetReturnPolicyOk() (*string, bool)`

GetReturnPolicyOk returns a tuple with the ReturnPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnPolicy

`func (o *ReceiptCreate) SetReturnPolicy(v string)`

SetReturnPolicy sets ReturnPolicy field to given value.

### HasReturnPolicy

`func (o *ReceiptCreate) HasReturnPolicy() bool`

HasReturnPolicy returns a boolean if a field has been set.

### SetReturnPolicyNil

`func (o *ReceiptCreate) SetReturnPolicyNil(b bool)`

 SetReturnPolicyNil sets the value for ReturnPolicy to be an explicit nil

### UnsetReturnPolicy
`func (o *ReceiptCreate) UnsetReturnPolicy()`

UnsetReturnPolicy ensures that no value is present for ReturnPolicy, not even an explicit nil
### GetOffers

`func (o *ReceiptCreate) GetOffers() []string`

GetOffers returns the Offers field if non-nil, zero value otherwise.

### GetOffersOk

`func (o *ReceiptCreate) GetOffersOk() (*[]string, bool)`

GetOffersOk returns a tuple with the Offers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffers

`func (o *ReceiptCreate) SetOffers(v []string)`

SetOffers sets Offers field to given value.

### HasOffers

`func (o *ReceiptCreate) HasOffers() bool`

HasOffers returns a boolean if a field has been set.

### SetOffersNil

`func (o *ReceiptCreate) SetOffersNil(b bool)`

 SetOffersNil sets the value for Offers to be an explicit nil

### UnsetOffers
`func (o *ReceiptCreate) UnsetOffers()`

UnsetOffers ensures that no value is present for Offers, not even an explicit nil
### GetOfferPolicies

`func (o *ReceiptCreate) GetOfferPolicies() []OfferPolicyInfo`

GetOfferPolicies returns the OfferPolicies field if non-nil, zero value otherwise.

### GetOfferPoliciesOk

`func (o *ReceiptCreate) GetOfferPoliciesOk() (*[]OfferPolicyInfo, bool)`

GetOfferPoliciesOk returns a tuple with the OfferPolicies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOfferPolicies

`func (o *ReceiptCreate) SetOfferPolicies(v []OfferPolicyInfo)`

SetOfferPolicies sets OfferPolicies field to given value.

### HasOfferPolicies

`func (o *ReceiptCreate) HasOfferPolicies() bool`

HasOfferPolicies returns a boolean if a field has been set.

### GetFeedbackUrl

`func (o *ReceiptCreate) GetFeedbackUrl() string`

GetFeedbackUrl returns the FeedbackUrl field if non-nil, zero value otherwise.

### GetFeedbackUrlOk

`func (o *ReceiptCreate) GetFeedbackUrlOk() (*string, bool)`

GetFeedbackUrlOk returns a tuple with the FeedbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeedbackUrl

`func (o *ReceiptCreate) SetFeedbackUrl(v string)`

SetFeedbackUrl sets FeedbackUrl field to given value.

### HasFeedbackUrl

`func (o *ReceiptCreate) HasFeedbackUrl() bool`

HasFeedbackUrl returns a boolean if a field has been set.

### SetFeedbackUrlNil

`func (o *ReceiptCreate) SetFeedbackUrlNil(b bool)`

 SetFeedbackUrlNil sets the value for FeedbackUrl to be an explicit nil

### UnsetFeedbackUrl
`func (o *ReceiptCreate) UnsetFeedbackUrl()`

UnsetFeedbackUrl ensures that no value is present for FeedbackUrl, not even an explicit nil
### GetLoyaltyInfo

`func (o *ReceiptCreate) GetLoyaltyInfo() string`

GetLoyaltyInfo returns the LoyaltyInfo field if non-nil, zero value otherwise.

### GetLoyaltyInfoOk

`func (o *ReceiptCreate) GetLoyaltyInfoOk() (*string, bool)`

GetLoyaltyInfoOk returns a tuple with the LoyaltyInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoyaltyInfo

`func (o *ReceiptCreate) SetLoyaltyInfo(v string)`

SetLoyaltyInfo sets LoyaltyInfo field to given value.

### HasLoyaltyInfo

`func (o *ReceiptCreate) HasLoyaltyInfo() bool`

HasLoyaltyInfo returns a boolean if a field has been set.

### SetLoyaltyInfoNil

`func (o *ReceiptCreate) SetLoyaltyInfoNil(b bool)`

 SetLoyaltyInfoNil sets the value for LoyaltyInfo to be an explicit nil

### UnsetLoyaltyInfo
`func (o *ReceiptCreate) UnsetLoyaltyInfo()`

UnsetLoyaltyInfo ensures that no value is present for LoyaltyInfo, not even an explicit nil
### GetMerchantDetails

`func (o *ReceiptCreate) GetMerchantDetails() MerchantDetails`

GetMerchantDetails returns the MerchantDetails field if non-nil, zero value otherwise.

### GetMerchantDetailsOk

`func (o *ReceiptCreate) GetMerchantDetailsOk() (*MerchantDetails, bool)`

GetMerchantDetailsOk returns a tuple with the MerchantDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantDetails

`func (o *ReceiptCreate) SetMerchantDetails(v MerchantDetails)`

SetMerchantDetails sets MerchantDetails field to given value.

### HasMerchantDetails

`func (o *ReceiptCreate) HasMerchantDetails() bool`

HasMerchantDetails returns a boolean if a field has been set.

### SetMerchantDetailsNil

`func (o *ReceiptCreate) SetMerchantDetailsNil(b bool)`

 SetMerchantDetailsNil sets the value for MerchantDetails to be an explicit nil

### UnsetMerchantDetails
`func (o *ReceiptCreate) UnsetMerchantDetails()`

UnsetMerchantDetails ensures that no value is present for MerchantDetails, not even an explicit nil
### GetAdjustments

`func (o *ReceiptCreate) GetAdjustments() []ReceiptAdjustment`

GetAdjustments returns the Adjustments field if non-nil, zero value otherwise.

### GetAdjustmentsOk

`func (o *ReceiptCreate) GetAdjustmentsOk() (*[]ReceiptAdjustment, bool)`

GetAdjustmentsOk returns a tuple with the Adjustments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustments

`func (o *ReceiptCreate) SetAdjustments(v []ReceiptAdjustment)`

SetAdjustments sets Adjustments field to given value.

### HasAdjustments

`func (o *ReceiptCreate) HasAdjustments() bool`

HasAdjustments returns a boolean if a field has been set.

### GetTransactionReferences

`func (o *ReceiptCreate) GetTransactionReferences() []TransactionReference`

GetTransactionReferences returns the TransactionReferences field if non-nil, zero value otherwise.

### GetTransactionReferencesOk

`func (o *ReceiptCreate) GetTransactionReferencesOk() (*[]TransactionReference, bool)`

GetTransactionReferencesOk returns a tuple with the TransactionReferences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionReferences

`func (o *ReceiptCreate) SetTransactionReferences(v []TransactionReference)`

SetTransactionReferences sets TransactionReferences field to given value.

### HasTransactionReferences

`func (o *ReceiptCreate) HasTransactionReferences() bool`

HasTransactionReferences returns a boolean if a field has been set.

### GetWarranties

`func (o *ReceiptCreate) GetWarranties() []WarrantyInfo`

GetWarranties returns the Warranties field if non-nil, zero value otherwise.

### GetWarrantiesOk

`func (o *ReceiptCreate) GetWarrantiesOk() (*[]WarrantyInfo, bool)`

GetWarrantiesOk returns a tuple with the Warranties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarranties

`func (o *ReceiptCreate) SetWarranties(v []WarrantyInfo)`

SetWarranties sets Warranties field to given value.

### HasWarranties

`func (o *ReceiptCreate) HasWarranties() bool`

HasWarranties returns a boolean if a field has been set.

### GetInsights

`func (o *ReceiptCreate) GetInsights() ReceiptInsights`

GetInsights returns the Insights field if non-nil, zero value otherwise.

### GetInsightsOk

`func (o *ReceiptCreate) GetInsightsOk() (*ReceiptInsights, bool)`

GetInsightsOk returns a tuple with the Insights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsights

`func (o *ReceiptCreate) SetInsights(v ReceiptInsights)`

SetInsights sets Insights field to given value.

### HasInsights

`func (o *ReceiptCreate) HasInsights() bool`

HasInsights returns a boolean if a field has been set.

### SetInsightsNil

`func (o *ReceiptCreate) SetInsightsNil(b bool)`

 SetInsightsNil sets the value for Insights to be an explicit nil

### UnsetInsights
`func (o *ReceiptCreate) UnsetInsights()`

UnsetInsights ensures that no value is present for Insights, not even an explicit nil
### GetReturnInsights

`func (o *ReceiptCreate) GetReturnInsights() ReturnInsights`

GetReturnInsights returns the ReturnInsights field if non-nil, zero value otherwise.

### GetReturnInsightsOk

`func (o *ReceiptCreate) GetReturnInsightsOk() (*ReturnInsights, bool)`

GetReturnInsightsOk returns a tuple with the ReturnInsights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnInsights

`func (o *ReceiptCreate) SetReturnInsights(v ReturnInsights)`

SetReturnInsights sets ReturnInsights field to given value.

### HasReturnInsights

`func (o *ReceiptCreate) HasReturnInsights() bool`

HasReturnInsights returns a boolean if a field has been set.

### SetReturnInsightsNil

`func (o *ReceiptCreate) SetReturnInsightsNil(b bool)`

 SetReturnInsightsNil sets the value for ReturnInsights to be an explicit nil

### UnsetReturnInsights
`func (o *ReceiptCreate) UnsetReturnInsights()`

UnsetReturnInsights ensures that no value is present for ReturnInsights, not even an explicit nil
### GetQrExpiryMinutes

`func (o *ReceiptCreate) GetQrExpiryMinutes() int32`

GetQrExpiryMinutes returns the QrExpiryMinutes field if non-nil, zero value otherwise.

### GetQrExpiryMinutesOk

`func (o *ReceiptCreate) GetQrExpiryMinutesOk() (*int32, bool)`

GetQrExpiryMinutesOk returns a tuple with the QrExpiryMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrExpiryMinutes

`func (o *ReceiptCreate) SetQrExpiryMinutes(v int32)`

SetQrExpiryMinutes sets QrExpiryMinutes field to given value.

### HasQrExpiryMinutes

`func (o *ReceiptCreate) HasQrExpiryMinutes() bool`

HasQrExpiryMinutes returns a boolean if a field has been set.

### SetQrExpiryMinutesNil

`func (o *ReceiptCreate) SetQrExpiryMinutesNil(b bool)`

 SetQrExpiryMinutesNil sets the value for QrExpiryMinutes to be an explicit nil

### UnsetQrExpiryMinutes
`func (o *ReceiptCreate) UnsetQrExpiryMinutes()`

UnsetQrExpiryMinutes ensures that no value is present for QrExpiryMinutes, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


