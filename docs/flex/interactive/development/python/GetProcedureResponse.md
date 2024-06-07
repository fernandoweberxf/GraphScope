# GetProcedureResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**description** | **str** |  | [optional] 
**type** | **str** |  | 
**query** | **str** |  | 
**id** | **str** |  | [optional] 
**library** | **str** |  | [optional] 
**params** | [**List[Parameter]**](Parameter.md) |  | [optional] 
**returns** | [**List[Parameter]**](Parameter.md) |  | [optional] 
**enable** | **bool** |  | [optional] 
**bound_graph** | **str** |  | [optional] 
**runnable** | **bool** |  | [optional] 
**creation_time** | **int** |  | [optional] 

## Example

```python
from interactive_sdk.openapi.models.get_procedure_response import GetProcedureResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetProcedureResponse from a JSON string
get_procedure_response_instance = GetProcedureResponse.from_json(json)
# print the JSON string representation of the object
print GetProcedureResponse.to_json()

# convert the object into a dict
get_procedure_response_dict = get_procedure_response_instance.to_dict()
# create an instance of GetProcedureResponse from a dict
get_procedure_response_form_dict = get_procedure_response.from_dict(get_procedure_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

