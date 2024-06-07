# EdgeMapping


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type_triplet** | [**EdgeMappingTypeTriplet**](EdgeMappingTypeTriplet.md) |  | [optional] 
**inputs** | **List[str]** |  | [optional] 
**source_vertex_mappings** | [**List[EdgeMappingSourceVertexMappingsInner]**](EdgeMappingSourceVertexMappingsInner.md) |  | [optional] 
**destination_vertex_mappings** | [**List[EdgeMappingDestinationVertexMappingsInner]**](EdgeMappingDestinationVertexMappingsInner.md) |  | [optional] 
**column_mappings** | [**List[ColumnMapping]**](ColumnMapping.md) |  | [optional] 

## Example

```python
from interactive_sdk.openapi.models.edge_mapping import EdgeMapping

# TODO update the JSON string below
json = "{}"
# create an instance of EdgeMapping from a JSON string
edge_mapping_instance = EdgeMapping.from_json(json)
# print the JSON string representation of the object
print EdgeMapping.to_json()

# convert the object into a dict
edge_mapping_dict = edge_mapping_instance.to_dict()
# create an instance of EdgeMapping from a dict
edge_mapping_form_dict = edge_mapping.from_dict(edge_mapping_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

