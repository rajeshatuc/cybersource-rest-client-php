# InvoicingV2InvoicesGet200ResponseInvoiceHistory

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event** | **string** | The event triggered for the invoice.  Possible values:  - &#x60;CREATE&#x60;  - &#x60;UPDATE&#x60;  - &#x60;SEND&#x60;  - &#x60;RESEND&#x60;  - &#x60;REMINDER&#x60;  - &#x60;PAYMENT&#x60;  - &#x60;CANCEL&#x60; | [optional] 
**date** | [**\DateTime**](Date.md) | The invoice due date. This field is required for creating an invoice. Format: &#x60;YYYY-MM-DD&#x60;, where &#x60;YYYY&#x60; &#x3D; year, &#x60;MM&#x60; &#x3D; month, and &#x60;DD&#x60; &#x3D; day | [optional] 
**transactionDetails** | [**\CyberSource\Model\InvoicingV2InvoicesGet200ResponseTransactionDetails**](InvoicingV2InvoicesGet200ResponseTransactionDetails.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


