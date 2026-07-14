# XeroRuby::Accounting::TrackingReference

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tracking_category_id** | **String** | The Xero identifier for a tracking category | 
**tracking_option_id** | **String** | The Xero identifier for a tracking category option | 
**name** | **String** | The name of the tracking category | [optional] 
**option** | **String** | See Tracking Options | [optional] 

## Code Sample

```ruby
require 'XeroRuby::Accounting'

instance = XeroRuby::Accounting::TrackingReference.new(tracking_category_id: null,
                                 tracking_option_id: null,
                                 name: null,
                                 option: null)
```


