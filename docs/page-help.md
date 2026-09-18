This section includes topics for each of the pages within the app. If you have navigated to this page from within the app from a specific page, it means there is no context-sensitive help for the page you navigated from.

To learn more about BPAY payments click [here](index.md).

## Capgemini BPAY Setup

|Type|Caption|Description|
|-|-|-|
|Field|Sandbox Tenant Id|Specifies a tenant id to be used for testing your subscription. When this app is running in a test environment (online Sandbox, docker Sandbox, or the company name begins with CRONUS) this app is free to use and no subscription check is made. Use this field to enter a tenant id to test subscription functionality in a test environment.|
|Field|PowerShell Command|Specifies a PowerShell command that can be used to test for a valid license for the current tenant id or the Sandbox Tenant Id. Copy and paste this command into a PowerShell command prompt.|
|Action|Test Subscription|Send a request to the license server to verify that your tenant has a valid subscription for this extension.|

## BPAY Transaction

|Type|Caption|Description|
|-|-|-|
|Field|Transaction No.|Specifies the value of the Transaction No. field.|
|Field|Payment Date|Specifies the value of the Payment Date field.|
|Field|Payer Name|Specifies the value of the Pay From Bank Account field.|
|Field|Pay From Bank Account|Specifies the value of the Pay From Bank Account field.|
|Field|BPAY Bank Payment Format|Specifies the value of the BPAY Bank Payment Format field.|
|Field|Total Amount|Specifies the value of the Total Amount field.|
|Action|Download BPAY File|Downloads the file to be loaded into the bank software representing this BPAY transaction.|
|Action|Cancel BPAY Transaction|Marks the status of this BPAY Transaction as cancelled which will allow the payment journal lines to be modified.|
|Sub page|BPAY Transaction Lines|[BPAY Transaction Lines](#bpay-transaction-lines)|

## BPAY Transaction Lines

|Type|Caption|Description|
|-|-|-|
|Field|Account Name|Specifies the value of the Account Name field.|
|Field|Document No.|Specifies the value of the Document No. field.|
|Field|Vendor Invoice No./Ext Doc No.|Specifies the value of the External Document No. field.|
|Field|BPAY Biller Code|Specifies the value of the BPAY Biller Code field.|
|Field|Customer Reference No.|Specifies the value of the Customer Reference No. field.|

## BPAY Transactions

|Type|Caption|Description|
|-|-|-|
|Field|Created On|Specifies the value of the Created On field.|
|Field|Transaction No.|Specifies the value of the Transaction No. field.|
|Field|Pay From Bank Account|Specifies the value of the Pay From Bank Account field.|
|Field|Payment Date|Specifies the value of the Payment Date field.|
|Field|Status|Specifies the value of the Status field.|
|Field|Exported On|Specifies the value of the Exported On field.|
|Field|Exported By|Specifies the value of the Exported By field.|
|Field|Total Amount|Specifies the value of the Total Amount field.|
|Action|Download BPAY File|Downloads the file to be loaded into the bank software representing this bank transfer transaction.|
|Action|Cancel BPAY Transaction|Marks the status of this BPAY Transaction as cancelled which will allow the payment journal lines to be modified.|
|Action|BPAY Transaction Lines|Show the transaction line associated to a register.|

## Vendor BPAY Account Card

|Type|Caption|Description|
|-|-|-|
|Field|Code|Specifies the value of the Code field.|
|Field|Name|Specifies the value of the Name field.|
|Field|BPAY Biller Code|Specifies the value of the BPAY Biller Code field.|
|Field|Customer Reference No.(CRN)|Specifies the value of the Customer Reference No.(CRN) field.|

## Vendor BPAY Accounts

|Type|Caption|Description|
|-|-|-|
|Field|Code|Specifies the value of the Code field.|
|Field|Name|Specifies the value of the Name field.|
|Field|BPAY Biller Code|Specifies the value of the BPAY Biller Code field.|
|Field|Customer Reference No.(CRN)|Specifies the value of the Customer Reference No.(CRN) field.|

## Page Extensions

## Payment Journal

|Type|Caption|Description|
|-|-|-|
|Action|Create and Download BPAY File|Shows an options page where the pay from bank, file type, and other settings can be configured. Once the values are correct, the BPAY file will be downloaded and the status of the BPAY Transaction will change to indicate the transaction has been exported. This will block the payment journal from further modification until the transaction is cancelled or the journal is posted.|
|Action|Cancel BPAY Transaction|Marks the status of this BPAY Transaction as cancelled which will allow the payment journal lines to be modified.|
|Action|Download BPAY File|Downloads the file to be loaded into the bank software representing this bank transfer transaction.|
|Action|BPAY Transaction|Shows the BPAY Transaction that has been generated for this payment journal batch.|
|Action|Suggest BPAY Payments|Create BPAY payment suggestions as lines in the payment journal.|

## Vendor Card

|Type|Caption|Description|
|-|-|-|
|Action|BPAY Accounts|Open the list of the vendor's BPAY accounts|

## Vendor List

|Type|Caption|Description|
|-|-|-|
|Action|BPAY Accounts|Open the list of the vendor's BPAY accounts|



