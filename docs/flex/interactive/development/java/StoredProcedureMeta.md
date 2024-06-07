

# StoredProcedureMeta


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**name** | **String** |  |  |
|**description** | **String** |  |  [optional] |
|**type** | [**TypeEnum**](#TypeEnum) |  |  |
|**query** | **String** |  |  |
|**id** | **String** |  |  [optional] |
|**library** | **String** |  |  [optional] |
|**params** | [**List&lt;Parameter&gt;**](Parameter.md) |  |  [optional] |
|**returns** | [**List&lt;Parameter&gt;**](Parameter.md) |  |  [optional] |
|**enable** | **Boolean** |  |  [optional] |



## Enum: TypeEnum

| Name | Value |
|---- | -----|
| CPP | &quot;cpp&quot; |
| CYPHER | &quot;cypher&quot; |


