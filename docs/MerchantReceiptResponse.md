# MerchantReceiptResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**PublicToken** | **string** |  | 
**Barcode** | Pointer to [**NullableBarcode**](Barcode.md) |  | [optional] 
**MerchantReceiptId** | Pointer to **NullableString** |  | [optional] 
**MerchantName** | Pointer to **NullableString** |  | [optional] 
**MerchantLogo** | Pointer to **NullableString** |  | [optional] 
**StoreId** | **string** |  | 
**OrganisationId** | **string** |  | 
**TransactionDate** | **time.Time** |  | 
**OrderNumber** | Pointer to **NullableString** |  | [optional] 
**Cashier** | Pointer to **NullableString** |  | [optional] 
**Items** | [**[]ReceiptItemResponse**](ReceiptItemResponse.md) |  | 
**Subtotal** | **string** |  | 
**TaxAmount** | **string** |  | 
**DiscountAmount** | **string** |  | 
**TipAmount** | **string** |  | 
**TotalAmount** | **string** |  | 
**Currency** | **string** |  | 
**PaymentInfo** | [**[]PaymentInfoResponse**](PaymentInfoResponse.md) |  | 
**QrCodeUrl** | **string** |  | 
**QrToken** | **string** |  | 
**QrExpiresAt** | **NullableTime** |  | 
**ReceiptUrl** | **string** |  | 
**PdfUrl** | Pointer to **NullableString** |  | [optional] 
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
**AccessCount** | **int32** |  | 
**LastAccessed** | Pointer to **NullableTime** |  | [optional] 
**Status** | **string** |  | 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewMerchantReceiptResponse

`func NewMerchantReceiptResponse(id string, publicToken string, storeId string, organisationId string, transactionDate time.Time, items []ReceiptItemResponse, subtotal string, taxAmount string, discountAmount string, tipAmount string, totalAmount string, currency string, paymentInfo []PaymentInfoResponse, qrCodeUrl string, qrToken string, qrExpiresAt NullableTime, receiptUrl string, accessCount int32, status string, createdAt time.Time, updatedAt time.Time, ) *MerchantReceiptResponse`

NewMerchantReceiptResponse instantiates a new MerchantReceiptResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMerchantReceiptResponseWithDefaults

`func NewMerchantReceiptResponseWithDefaults() *MerchantReceiptResponse`

NewMerchantReceiptResponseWithDefaults instantiates a new MerchantReceiptResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MerchantReceiptResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MerchantReceiptResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MerchantReceiptResponse) SetId(v string)`

SetId sets Id field to given value.


### GetPublicToken

`func (o *MerchantReceiptResponse) GetPublicToken() string`

GetPublicToken returns the PublicToken field if non-nil, zero value otherwise.

### GetPublicTokenOk

`func (o *MerchantReceiptResponse) GetPublicTokenOk() (*string, bool)`

GetPublicTokenOk returns a tuple with the PublicToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicToken

`func (o *MerchantReceiptResponse) SetPublicToken(v string)`

SetPublicToken sets PublicToken field to given value.


### GetBarcode

`func (o *MerchantReceiptResponse) GetBarcode() Barcode`

GetBarcode returns the Barcode field if non-nil, zero value otherwise.

### GetBarcodeOk

`func (o *MerchantReceiptResponse) GetBarcodeOk() (*Barcode, bool)`

GetBarcodeOk returns a tuple with the Barcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBarcode

`func (o *MerchantReceiptResponse) SetBarcode(v Barcode)`

SetBarcode sets Barcode field to given value.

### HasBarcode

`func (o *MerchantReceiptResponse) HasBarcode() bool`

HasBarcode returns a boolean if a field has been set.

### SetBarcodeNil

`func (o *MerchantReceiptResponse) SetBarcodeNil(b bool)`

 SetBarcodeNil sets the value for Barcode to be an explicit nil

### UnsetBarcode
`func (o *MerchantReceiptResponse) UnsetBarcode()`

UnsetBarcode ensures that no value is present for Barcode, not even an explicit nil
### GetMerchantReceiptId

`func (o *MerchantReceiptResponse) GetMerchantReceiptId() string`

GetMerchantReceiptId returns the MerchantReceiptId field if non-nil, zero value otherwise.

### GetMerchantReceiptIdOk

`func (o *MerchantReceiptResponse) GetMerchantReceiptIdOk() (*string, bool)`

GetMerchantReceiptIdOk returns a tuple with the MerchantReceiptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantReceiptId

`func (o *MerchantReceiptResponse) SetMerchantReceiptId(v string)`

SetMerchantReceiptId sets MerchantReceiptId field to given value.

### HasMerchantReceiptId

`func (o *MerchantReceiptResponse) HasMerchantReceiptId() bool`

HasMerchantReceiptId returns a boolean if a field has been set.

### SetMerchantReceiptIdNil

`func (o *MerchantReceiptResponse) SetMerchantReceiptIdNil(b bool)`

 SetMerchantReceiptIdNil sets the value for MerchantReceiptId to be an explicit nil

### UnsetMerchantReceiptId
`func (o *MerchantReceiptResponse) UnsetMerchantReceiptId()`

UnsetMerchantReceiptId ensures that no value is present for MerchantReceiptId, not even an explicit nil
### GetMerchantName

`func (o *MerchantReceiptResponse) GetMerchantName() string`

GetMerchantName returns the MerchantName field if non-nil, zero value otherwise.

### GetMerchantNameOk

`func (o *MerchantReceiptResponse) GetMerchantNameOk() (*string, bool)`

GetMerchantNameOk returns a tuple with the MerchantName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantName

`func (o *MerchantReceiptResponse) SetMerchantName(v string)`

SetMerchantName sets MerchantName field to given value.

### HasMerchantName

`func (o *MerchantReceiptResponse) HasMerchantName() bool`

HasMerchantName returns a boolean if a field has been set.

### SetMerchantNameNil

`func (o *MerchantReceiptResponse) SetMerchantNameNil(b bool)`

 SetMerchantNameNil sets the value for MerchantName to be an explicit nil

### UnsetMerchantName
`func (o *MerchantReceiptResponse) UnsetMerchantName()`

UnsetMerchantName ensures that no value is present for MerchantName, not even an explicit nil
### GetMerchantLogo

`func (o *MerchantReceiptResponse) GetMerchantLogo() string`

GetMerchantLogo returns the MerchantLogo field if non-nil, zero value otherwise.

### GetMerchantLogoOk

`func (o *MerchantReceiptResponse) GetMerchantLogoOk() (*string, bool)`

GetMerchantLogoOk returns a tuple with the MerchantLogo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantLogo

`func (o *MerchantReceiptResponse) SetMerchantLogo(v string)`

SetMerchantLogo sets MerchantLogo field to given value.

### HasMerchantLogo

`func (o *MerchantReceiptResponse) HasMerchantLogo() bool`

HasMerchantLogo returns a boolean if a field has been set.

### SetMerchantLogoNil

`func (o *MerchantReceiptResponse) SetMerchantLogoNil(b bool)`

 SetMerchantLogoNil sets the value for MerchantLogo to be an explicit nil

### UnsetMerchantLogo
`func (o *MerchantReceiptResponse) UnsetMerchantLogo()`

UnsetMerchantLogo ensures that no value is present for MerchantLogo, not even an explicit nil
### GetStoreId

`func (o *MerchantReceiptResponse) GetStoreId() string`

GetStoreId returns the StoreId field if non-nil, zero value otherwise.

### GetStoreIdOk

`func (o *MerchantReceiptResponse) GetStoreIdOk() (*string, bool)`

GetStoreIdOk returns a tuple with the StoreId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreId

`func (o *MerchantReceiptResponse) SetStoreId(v string)`

SetStoreId sets StoreId field to given value.


### GetOrganisationId

`func (o *MerchantReceiptResponse) GetOrganisationId() string`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *MerchantReceiptResponse) GetOrganisationIdOk() (*string, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *MerchantReceiptResponse) SetOrganisationId(v string)`

SetOrganisationId sets OrganisationId field to given value.


### GetTransactionDate

`func (o *MerchantReceiptResponse) GetTransactionDate() time.Time`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *MerchantReceiptResponse) GetTransactionDateOk() (*time.Time, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *MerchantReceiptResponse) SetTransactionDate(v time.Time)`

SetTransactionDate sets TransactionDate field to given value.


### GetOrderNumber

`func (o *MerchantReceiptResponse) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *MerchantReceiptResponse) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *MerchantReceiptResponse) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *MerchantReceiptResponse) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### SetOrderNumberNil

`func (o *MerchantReceiptResponse) SetOrderNumberNil(b bool)`

 SetOrderNumberNil sets the value for OrderNumber to be an explicit nil

### UnsetOrderNumber
`func (o *MerchantReceiptResponse) UnsetOrderNumber()`

UnsetOrderNumber ensures that no value is present for OrderNumber, not even an explicit nil
### GetCashier

`func (o *MerchantReceiptResponse) GetCashier() string`

GetCashier returns the Cashier field if non-nil, zero value otherwise.

### GetCashierOk

`func (o *MerchantReceiptResponse) GetCashierOk() (*string, bool)`

GetCashierOk returns a tuple with the Cashier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCashier

`func (o *MerchantReceiptResponse) SetCashier(v string)`

SetCashier sets Cashier field to given value.

### HasCashier

`func (o *MerchantReceiptResponse) HasCashier() bool`

HasCashier returns a boolean if a field has been set.

### SetCashierNil

`func (o *MerchantReceiptResponse) SetCashierNil(b bool)`

 SetCashierNil sets the value for Cashier to be an explicit nil

### UnsetCashier
`func (o *MerchantReceiptResponse) UnsetCashier()`

UnsetCashier ensures that no value is present for Cashier, not even an explicit nil
### GetItems

`func (o *MerchantReceiptResponse) GetItems() []ReceiptItemResponse`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *MerchantReceiptResponse) GetItemsOk() (*[]ReceiptItemResponse, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *MerchantReceiptResponse) SetItems(v []ReceiptItemResponse)`

SetItems sets Items field to given value.


### GetSubtotal

`func (o *MerchantReceiptResponse) GetSubtotal() string`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *MerchantReceiptResponse) GetSubtotalOk() (*string, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *MerchantReceiptResponse) SetSubtotal(v string)`

SetSubtotal sets Subtotal field to given value.


### GetTaxAmount

`func (o *MerchantReceiptResponse) GetTaxAmount() string`

GetTaxAmount returns the TaxAmount field if non-nil, zero value otherwise.

### GetTaxAmountOk

`func (o *MerchantReceiptResponse) GetTaxAmountOk() (*string, bool)`

GetTaxAmountOk returns a tuple with the TaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmount

`func (o *MerchantReceiptResponse) SetTaxAmount(v string)`

SetTaxAmount sets TaxAmount field to given value.


### GetDiscountAmount

`func (o *MerchantReceiptResponse) GetDiscountAmount() string`

GetDiscountAmount returns the DiscountAmount field if non-nil, zero value otherwise.

### GetDiscountAmountOk

`func (o *MerchantReceiptResponse) GetDiscountAmountOk() (*string, bool)`

GetDiscountAmountOk returns a tuple with the DiscountAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountAmount

`func (o *MerchantReceiptResponse) SetDiscountAmount(v string)`

SetDiscountAmount sets DiscountAmount field to given value.


### GetTipAmount

`func (o *MerchantReceiptResponse) GetTipAmount() string`

GetTipAmount returns the TipAmount field if non-nil, zero value otherwise.

### GetTipAmountOk

`func (o *MerchantReceiptResponse) GetTipAmountOk() (*string, bool)`

GetTipAmountOk returns a tuple with the TipAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTipAmount

`func (o *MerchantReceiptResponse) SetTipAmount(v string)`

SetTipAmount sets TipAmount field to given value.


### GetTotalAmount

`func (o *MerchantReceiptResponse) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *MerchantReceiptResponse) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *MerchantReceiptResponse) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.


### GetCurrency

`func (o *MerchantReceiptResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *MerchantReceiptResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *MerchantReceiptResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetPaymentInfo

`func (o *MerchantReceiptResponse) GetPaymentInfo() []PaymentInfoResponse`

GetPaymentInfo returns the PaymentInfo field if non-nil, zero value otherwise.

### GetPaymentInfoOk

`func (o *MerchantReceiptResponse) GetPaymentInfoOk() (*[]PaymentInfoResponse, bool)`

GetPaymentInfoOk returns a tuple with the PaymentInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentInfo

`func (o *MerchantReceiptResponse) SetPaymentInfo(v []PaymentInfoResponse)`

SetPaymentInfo sets PaymentInfo field to given value.


### GetQrCodeUrl

`func (o *MerchantReceiptResponse) GetQrCodeUrl() string`

GetQrCodeUrl returns the QrCodeUrl field if non-nil, zero value otherwise.

### GetQrCodeUrlOk

`func (o *MerchantReceiptResponse) GetQrCodeUrlOk() (*string, bool)`

GetQrCodeUrlOk returns a tuple with the QrCodeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeUrl

`func (o *MerchantReceiptResponse) SetQrCodeUrl(v string)`

SetQrCodeUrl sets QrCodeUrl field to given value.


### GetQrToken

`func (o *MerchantReceiptResponse) GetQrToken() string`

GetQrToken returns the QrToken field if non-nil, zero value otherwise.

### GetQrTokenOk

`func (o *MerchantReceiptResponse) GetQrTokenOk() (*string, bool)`

GetQrTokenOk returns a tuple with the QrToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrToken

`func (o *MerchantReceiptResponse) SetQrToken(v string)`

SetQrToken sets QrToken field to given value.


### GetQrExpiresAt

`func (o *MerchantReceiptResponse) GetQrExpiresAt() time.Time`

GetQrExpiresAt returns the QrExpiresAt field if non-nil, zero value otherwise.

### GetQrExpiresAtOk

`func (o *MerchantReceiptResponse) GetQrExpiresAtOk() (*time.Time, bool)`

GetQrExpiresAtOk returns a tuple with the QrExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrExpiresAt

`func (o *MerchantReceiptResponse) SetQrExpiresAt(v time.Time)`

SetQrExpiresAt sets QrExpiresAt field to given value.


### SetQrExpiresAtNil

`func (o *MerchantReceiptResponse) SetQrExpiresAtNil(b bool)`

 SetQrExpiresAtNil sets the value for QrExpiresAt to be an explicit nil

### UnsetQrExpiresAt
`func (o *MerchantReceiptResponse) UnsetQrExpiresAt()`

UnsetQrExpiresAt ensures that no value is present for QrExpiresAt, not even an explicit nil
### GetReceiptUrl

`func (o *MerchantReceiptResponse) GetReceiptUrl() string`

GetReceiptUrl returns the ReceiptUrl field if non-nil, zero value otherwise.

### GetReceiptUrlOk

`func (o *MerchantReceiptResponse) GetReceiptUrlOk() (*string, bool)`

GetReceiptUrlOk returns a tuple with the ReceiptUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptUrl

`func (o *MerchantReceiptResponse) SetReceiptUrl(v string)`

SetReceiptUrl sets ReceiptUrl field to given value.


### GetPdfUrl

`func (o *MerchantReceiptResponse) GetPdfUrl() string`

GetPdfUrl returns the PdfUrl field if non-nil, zero value otherwise.

### GetPdfUrlOk

`func (o *MerchantReceiptResponse) GetPdfUrlOk() (*string, bool)`

GetPdfUrlOk returns a tuple with the PdfUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPdfUrl

`func (o *MerchantReceiptResponse) SetPdfUrl(v string)`

SetPdfUrl sets PdfUrl field to given value.

### HasPdfUrl

`func (o *MerchantReceiptResponse) HasPdfUrl() bool`

HasPdfUrl returns a boolean if a field has been set.

### SetPdfUrlNil

`func (o *MerchantReceiptResponse) SetPdfUrlNil(b bool)`

 SetPdfUrlNil sets the value for PdfUrl to be an explicit nil

### UnsetPdfUrl
`func (o *MerchantReceiptResponse) UnsetPdfUrl()`

UnsetPdfUrl ensures that no value is present for PdfUrl, not even an explicit nil
### GetNotes

`func (o *MerchantReceiptResponse) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *MerchantReceiptResponse) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *MerchantReceiptResponse) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *MerchantReceiptResponse) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *MerchantReceiptResponse) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *MerchantReceiptResponse) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetReturnPolicy

`func (o *MerchantReceiptResponse) GetReturnPolicy() string`

GetReturnPolicy returns the ReturnPolicy field if non-nil, zero value otherwise.

### GetReturnPolicyOk

`func (o *MerchantReceiptResponse) GetReturnPolicyOk() (*string, bool)`

GetReturnPolicyOk returns a tuple with the ReturnPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnPolicy

`func (o *MerchantReceiptResponse) SetReturnPolicy(v string)`

SetReturnPolicy sets ReturnPolicy field to given value.

### HasReturnPolicy

`func (o *MerchantReceiptResponse) HasReturnPolicy() bool`

HasReturnPolicy returns a boolean if a field has been set.

### SetReturnPolicyNil

`func (o *MerchantReceiptResponse) SetReturnPolicyNil(b bool)`

 SetReturnPolicyNil sets the value for ReturnPolicy to be an explicit nil

### UnsetReturnPolicy
`func (o *MerchantReceiptResponse) UnsetReturnPolicy()`

UnsetReturnPolicy ensures that no value is present for ReturnPolicy, not even an explicit nil
### GetOffers

`func (o *MerchantReceiptResponse) GetOffers() []string`

GetOffers returns the Offers field if non-nil, zero value otherwise.

### GetOffersOk

`func (o *MerchantReceiptResponse) GetOffersOk() (*[]string, bool)`

GetOffersOk returns a tuple with the Offers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffers

`func (o *MerchantReceiptResponse) SetOffers(v []string)`

SetOffers sets Offers field to given value.

### HasOffers

`func (o *MerchantReceiptResponse) HasOffers() bool`

HasOffers returns a boolean if a field has been set.

### SetOffersNil

`func (o *MerchantReceiptResponse) SetOffersNil(b bool)`

 SetOffersNil sets the value for Offers to be an explicit nil

### UnsetOffers
`func (o *MerchantReceiptResponse) UnsetOffers()`

UnsetOffers ensures that no value is present for Offers, not even an explicit nil
### GetOfferPolicies

`func (o *MerchantReceiptResponse) GetOfferPolicies() []OfferPolicyInfo`

GetOfferPolicies returns the OfferPolicies field if non-nil, zero value otherwise.

### GetOfferPoliciesOk

`func (o *MerchantReceiptResponse) GetOfferPoliciesOk() (*[]OfferPolicyInfo, bool)`

GetOfferPoliciesOk returns a tuple with the OfferPolicies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOfferPolicies

`func (o *MerchantReceiptResponse) SetOfferPolicies(v []OfferPolicyInfo)`

SetOfferPolicies sets OfferPolicies field to given value.

### HasOfferPolicies

`func (o *MerchantReceiptResponse) HasOfferPolicies() bool`

HasOfferPolicies returns a boolean if a field has been set.

### GetFeedbackUrl

`func (o *MerchantReceiptResponse) GetFeedbackUrl() string`

GetFeedbackUrl returns the FeedbackUrl field if non-nil, zero value otherwise.

### GetFeedbackUrlOk

`func (o *MerchantReceiptResponse) GetFeedbackUrlOk() (*string, bool)`

GetFeedbackUrlOk returns a tuple with the FeedbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeedbackUrl

`func (o *MerchantReceiptResponse) SetFeedbackUrl(v string)`

SetFeedbackUrl sets FeedbackUrl field to given value.

### HasFeedbackUrl

`func (o *MerchantReceiptResponse) HasFeedbackUrl() bool`

HasFeedbackUrl returns a boolean if a field has been set.

### SetFeedbackUrlNil

`func (o *MerchantReceiptResponse) SetFeedbackUrlNil(b bool)`

 SetFeedbackUrlNil sets the value for FeedbackUrl to be an explicit nil

### UnsetFeedbackUrl
`func (o *MerchantReceiptResponse) UnsetFeedbackUrl()`

UnsetFeedbackUrl ensures that no value is present for FeedbackUrl, not even an explicit nil
### GetLoyaltyInfo

`func (o *MerchantReceiptResponse) GetLoyaltyInfo() string`

GetLoyaltyInfo returns the LoyaltyInfo field if non-nil, zero value otherwise.

### GetLoyaltyInfoOk

`func (o *MerchantReceiptResponse) GetLoyaltyInfoOk() (*string, bool)`

GetLoyaltyInfoOk returns a tuple with the LoyaltyInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoyaltyInfo

`func (o *MerchantReceiptResponse) SetLoyaltyInfo(v string)`

SetLoyaltyInfo sets LoyaltyInfo field to given value.

### HasLoyaltyInfo

`func (o *MerchantReceiptResponse) HasLoyaltyInfo() bool`

HasLoyaltyInfo returns a boolean if a field has been set.

### SetLoyaltyInfoNil

`func (o *MerchantReceiptResponse) SetLoyaltyInfoNil(b bool)`

 SetLoyaltyInfoNil sets the value for LoyaltyInfo to be an explicit nil

### UnsetLoyaltyInfo
`func (o *MerchantReceiptResponse) UnsetLoyaltyInfo()`

UnsetLoyaltyInfo ensures that no value is present for LoyaltyInfo, not even an explicit nil
### GetMerchantDetails

`func (o *MerchantReceiptResponse) GetMerchantDetails() MerchantDetails`

GetMerchantDetails returns the MerchantDetails field if non-nil, zero value otherwise.

### GetMerchantDetailsOk

`func (o *MerchantReceiptResponse) GetMerchantDetailsOk() (*MerchantDetails, bool)`

GetMerchantDetailsOk returns a tuple with the MerchantDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantDetails

`func (o *MerchantReceiptResponse) SetMerchantDetails(v MerchantDetails)`

SetMerchantDetails sets MerchantDetails field to given value.

### HasMerchantDetails

`func (o *MerchantReceiptResponse) HasMerchantDetails() bool`

HasMerchantDetails returns a boolean if a field has been set.

### SetMerchantDetailsNil

`func (o *MerchantReceiptResponse) SetMerchantDetailsNil(b bool)`

 SetMerchantDetailsNil sets the value for MerchantDetails to be an explicit nil

### UnsetMerchantDetails
`func (o *MerchantReceiptResponse) UnsetMerchantDetails()`

UnsetMerchantDetails ensures that no value is present for MerchantDetails, not even an explicit nil
### GetAdjustments

`func (o *MerchantReceiptResponse) GetAdjustments() []ReceiptAdjustment`

GetAdjustments returns the Adjustments field if non-nil, zero value otherwise.

### GetAdjustmentsOk

`func (o *MerchantReceiptResponse) GetAdjustmentsOk() (*[]ReceiptAdjustment, bool)`

GetAdjustmentsOk returns a tuple with the Adjustments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustments

`func (o *MerchantReceiptResponse) SetAdjustments(v []ReceiptAdjustment)`

SetAdjustments sets Adjustments field to given value.

### HasAdjustments

`func (o *MerchantReceiptResponse) HasAdjustments() bool`

HasAdjustments returns a boolean if a field has been set.

### GetTransactionReferences

`func (o *MerchantReceiptResponse) GetTransactionReferences() []TransactionReference`

GetTransactionReferences returns the TransactionReferences field if non-nil, zero value otherwise.

### GetTransactionReferencesOk

`func (o *MerchantReceiptResponse) GetTransactionReferencesOk() (*[]TransactionReference, bool)`

GetTransactionReferencesOk returns a tuple with the TransactionReferences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionReferences

`func (o *MerchantReceiptResponse) SetTransactionReferences(v []TransactionReference)`

SetTransactionReferences sets TransactionReferences field to given value.

### HasTransactionReferences

`func (o *MerchantReceiptResponse) HasTransactionReferences() bool`

HasTransactionReferences returns a boolean if a field has been set.

### GetWarranties

`func (o *MerchantReceiptResponse) GetWarranties() []WarrantyInfo`

GetWarranties returns the Warranties field if non-nil, zero value otherwise.

### GetWarrantiesOk

`func (o *MerchantReceiptResponse) GetWarrantiesOk() (*[]WarrantyInfo, bool)`

GetWarrantiesOk returns a tuple with the Warranties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarranties

`func (o *MerchantReceiptResponse) SetWarranties(v []WarrantyInfo)`

SetWarranties sets Warranties field to given value.

### HasWarranties

`func (o *MerchantReceiptResponse) HasWarranties() bool`

HasWarranties returns a boolean if a field has been set.

### GetInsights

`func (o *MerchantReceiptResponse) GetInsights() ReceiptInsights`

GetInsights returns the Insights field if non-nil, zero value otherwise.

### GetInsightsOk

`func (o *MerchantReceiptResponse) GetInsightsOk() (*ReceiptInsights, bool)`

GetInsightsOk returns a tuple with the Insights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsights

`func (o *MerchantReceiptResponse) SetInsights(v ReceiptInsights)`

SetInsights sets Insights field to given value.

### HasInsights

`func (o *MerchantReceiptResponse) HasInsights() bool`

HasInsights returns a boolean if a field has been set.

### SetInsightsNil

`func (o *MerchantReceiptResponse) SetInsightsNil(b bool)`

 SetInsightsNil sets the value for Insights to be an explicit nil

### UnsetInsights
`func (o *MerchantReceiptResponse) UnsetInsights()`

UnsetInsights ensures that no value is present for Insights, not even an explicit nil
### GetReturnInsights

`func (o *MerchantReceiptResponse) GetReturnInsights() ReturnInsights`

GetReturnInsights returns the ReturnInsights field if non-nil, zero value otherwise.

### GetReturnInsightsOk

`func (o *MerchantReceiptResponse) GetReturnInsightsOk() (*ReturnInsights, bool)`

GetReturnInsightsOk returns a tuple with the ReturnInsights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnInsights

`func (o *MerchantReceiptResponse) SetReturnInsights(v ReturnInsights)`

SetReturnInsights sets ReturnInsights field to given value.

### HasReturnInsights

`func (o *MerchantReceiptResponse) HasReturnInsights() bool`

HasReturnInsights returns a boolean if a field has been set.

### SetReturnInsightsNil

`func (o *MerchantReceiptResponse) SetReturnInsightsNil(b bool)`

 SetReturnInsightsNil sets the value for ReturnInsights to be an explicit nil

### UnsetReturnInsights
`func (o *MerchantReceiptResponse) UnsetReturnInsights()`

UnsetReturnInsights ensures that no value is present for ReturnInsights, not even an explicit nil
### GetAccessCount

`func (o *MerchantReceiptResponse) GetAccessCount() int32`

GetAccessCount returns the AccessCount field if non-nil, zero value otherwise.

### GetAccessCountOk

`func (o *MerchantReceiptResponse) GetAccessCountOk() (*int32, bool)`

GetAccessCountOk returns a tuple with the AccessCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessCount

`func (o *MerchantReceiptResponse) SetAccessCount(v int32)`

SetAccessCount sets AccessCount field to given value.


### GetLastAccessed

`func (o *MerchantReceiptResponse) GetLastAccessed() time.Time`

GetLastAccessed returns the LastAccessed field if non-nil, zero value otherwise.

### GetLastAccessedOk

`func (o *MerchantReceiptResponse) GetLastAccessedOk() (*time.Time, bool)`

GetLastAccessedOk returns a tuple with the LastAccessed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastAccessed

`func (o *MerchantReceiptResponse) SetLastAccessed(v time.Time)`

SetLastAccessed sets LastAccessed field to given value.

### HasLastAccessed

`func (o *MerchantReceiptResponse) HasLastAccessed() bool`

HasLastAccessed returns a boolean if a field has been set.

### SetLastAccessedNil

`func (o *MerchantReceiptResponse) SetLastAccessedNil(b bool)`

 SetLastAccessedNil sets the value for LastAccessed to be an explicit nil

### UnsetLastAccessed
`func (o *MerchantReceiptResponse) UnsetLastAccessed()`

UnsetLastAccessed ensures that no value is present for LastAccessed, not even an explicit nil
### GetStatus

`func (o *MerchantReceiptResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *MerchantReceiptResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *MerchantReceiptResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetExpiresAt

`func (o *MerchantReceiptResponse) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *MerchantReceiptResponse) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *MerchantReceiptResponse) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *MerchantReceiptResponse) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *MerchantReceiptResponse) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *MerchantReceiptResponse) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetCreatedAt

`func (o *MerchantReceiptResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MerchantReceiptResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MerchantReceiptResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *MerchantReceiptResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *MerchantReceiptResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *MerchantReceiptResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


