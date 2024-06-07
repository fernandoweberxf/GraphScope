# GetGraphSchemaResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vertex_types** | [**List[GetVertexType]**](GetVertexType.md) |  | [optional] 
**edge_types** | [**List[GetEdgeType]**](GetEdgeType.md) |  | [optional] 

## Example

```python
from interactive_sdk.openapi.models.get_graph_schema_response import GetGraphSchemaResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetGraphSchemaResponse from a JSON string
get_graph_schema_response_instance = GetGraphSchemaResponse.from_json(json)
# print the JSON string representation of the object
print GetGraphSchemaResponse.to_json()

# convert the object into a dict
get_graph_schema_response_dict = get_graph_schema_response_instance.to_dict()
# create an instance of GetGraphSchemaResponse from a dict
get_graph_schema_response_form_dict = get_graph_schema_response.from_dict(get_graph_schema_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

