# EdgeMappingTypeTriplet

source label -> [edge label] -> destination label

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edge** | **str** |  | [optional] 
**source_vertex** | **str** |  | [optional] 
**destination_vertex** | **str** |  | [optional] 

## Example

```python
from interactive_sdk.openapi.models.edge_mapping_type_triplet import EdgeMappingTypeTriplet

# TODO update the JSON string below
json = "{}"
# create an instance of EdgeMappingTypeTriplet from a JSON string
edge_mapping_type_triplet_instance = EdgeMappingTypeTriplet.from_json(json)
# print the JSON string representation of the object
print EdgeMappingTypeTriplet.to_json()

# convert the object into a dict
edge_mapping_type_triplet_dict = edge_mapping_type_triplet_instance.to_dict()
# create an instance of EdgeMappingTypeTriplet from a dict
edge_mapping_type_triplet_form_dict = edge_mapping_type_triplet.from_dict(edge_mapping_type_triplet_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

