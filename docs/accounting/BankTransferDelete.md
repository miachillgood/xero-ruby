# XeroRuby::Accounting::BankTransferDelete

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bank_transfer_id** | **String** | The Xero identifier for a bank transfer | 
**status** | **String** | The status of the bank transfer. | [default to &#39;DELETED&#39;]

## Code Sample

```ruby
require 'XeroRuby::Accounting'

instance = XeroRuby::Accounting::BankTransferDelete.new(bank_transfer_id: null,
                                 status: null)
```


