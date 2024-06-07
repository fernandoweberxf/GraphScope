# interactive_sdk.openapi.AdminServiceJobManagementApi

All URIs are relative to *https://virtserver.swaggerhub.com/GRAPHSCOPE/InteractiveAPI/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**delete_job_by_id**](AdminServiceJobManagementApi.md#delete_job_by_id) | **DELETE** /v1/job/{job_id} | 
[**get_job_by_id**](AdminServiceJobManagementApi.md#get_job_by_id) | **GET** /v1/job/{job_id} | 
[**list_jobs**](AdminServiceJobManagementApi.md#list_jobs) | **GET** /v1/job | 


# **delete_job_by_id**
> str delete_job_by_id(job_id)



### Example


```python
import time
import os
import interactive_sdk.openapi
from interactive_sdk.openapi.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://virtserver.swaggerhub.com/GRAPHSCOPE/InteractiveAPI/1.0.0
# See configuration.py for a list of all supported configuration parameters.
configuration = interactive_sdk.openapi.Configuration(
    host = "https://virtserver.swaggerhub.com/GRAPHSCOPE/InteractiveAPI/1.0.0"
)


# Enter a context with an instance of the API client
with interactive_sdk.openapi.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = interactive_sdk.openapi.AdminServiceJobManagementApi(api_client)
    job_id = 'job_id_example' # str | 

    try:
        api_response = api_instance.delete_job_by_id(job_id)
        print("The response of AdminServiceJobManagementApi->delete_job_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AdminServiceJobManagementApi->delete_job_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**|  | 

### Return type

**str**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_job_by_id**
> JobStatus get_job_by_id(job_id)



### Example


```python
import time
import os
import interactive_sdk.openapi
from interactive_sdk.openapi.models.job_status import JobStatus
from interactive_sdk.openapi.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://virtserver.swaggerhub.com/GRAPHSCOPE/InteractiveAPI/1.0.0
# See configuration.py for a list of all supported configuration parameters.
configuration = interactive_sdk.openapi.Configuration(
    host = "https://virtserver.swaggerhub.com/GRAPHSCOPE/InteractiveAPI/1.0.0"
)


# Enter a context with an instance of the API client
with interactive_sdk.openapi.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = interactive_sdk.openapi.AdminServiceJobManagementApi(api_client)
    job_id = 'job_id_example' # str | The id of the job, returned from POST /v1/graph/{graph_id}/dataloading

    try:
        api_response = api_instance.get_job_by_id(job_id)
        print("The response of AdminServiceJobManagementApi->get_job_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AdminServiceJobManagementApi->get_job_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**| The id of the job, returned from POST /v1/graph/{graph_id}/dataloading | 

### Return type

[**JobStatus**](JobStatus.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | successful operation |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_jobs**
> List[JobStatus] list_jobs()



### Example


```python
import time
import os
import interactive_sdk.openapi
from interactive_sdk.openapi.models.job_status import JobStatus
from interactive_sdk.openapi.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://virtserver.swaggerhub.com/GRAPHSCOPE/InteractiveAPI/1.0.0
# See configuration.py for a list of all supported configuration parameters.
configuration = interactive_sdk.openapi.Configuration(
    host = "https://virtserver.swaggerhub.com/GRAPHSCOPE/InteractiveAPI/1.0.0"
)


# Enter a context with an instance of the API client
with interactive_sdk.openapi.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = interactive_sdk.openapi.AdminServiceJobManagementApi(api_client)

    try:
        api_response = api_instance.list_jobs()
        print("The response of AdminServiceJobManagementApi->list_jobs:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AdminServiceJobManagementApi->list_jobs: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**List[JobStatus]**](JobStatus.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | successful operation |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)
