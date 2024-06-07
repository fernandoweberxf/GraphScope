# CreateGraphSchemaRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vertex_types** | [**List[CreateVertexType]**](CreateVertexType.md) |  | [optional] 
**edge_types** | [**List[CreateEdgeType]**](CreateEdgeType.md) |  | [optional] 

## Example

```python
from interactive_sdk.openapi.models.create_graph_schema_request import CreateGraphSchemaRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateGraphSchemaRequest from a JSON string
create_graph_schema_request_instance = CreateGraphSchemaRequest.from_json(json)
# print the JSON string representation of the object
print CreateGraphSchemaRequest.to_json()

# convert the object into a dict
create_graph_schema_request_dict = create_graph_schema_request_instance.to_dict()
# create an instance of CreateGraphSchemaRequest from a dict
create_graph_schema_request_form_dict = create_graph_schema_request.from_dict(create_graph_schema_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

