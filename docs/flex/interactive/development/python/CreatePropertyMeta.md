# CreatePropertyMeta


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_name** | **str** |  | [optional] 
**property_type** | [**GSDataType**](GSDataType.md) |  | [optional] 

## Example

```python
from interactive_sdk.openapi.models.create_property_meta import CreatePropertyMeta

# TODO update the JSON string below
json = "{}"
# create an instance of CreatePropertyMeta from a JSON string
create_property_meta_instance = CreatePropertyMeta.from_json(json)
# print the JSON string representation of the object
print CreatePropertyMeta.to_json()

# convert the object into a dict
create_property_meta_dict = create_property_meta_instance.to_dict()
# create an instance of CreatePropertyMeta from a dict
create_property_meta_form_dict = create_property_meta.from_dict(create_property_meta_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

