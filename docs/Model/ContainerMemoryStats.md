# # ContainerMemoryStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**usage** | **int** | Current &#x60;res_counter&#x60; usage for memory.  This field is Linux-specific and omitted for Windows containers. | [optional]
**max_usage** | **int** | Maximum usage ever recorded.  This field is Linux-specific and only supported on cgroups v1. It is omitted when using cgroups v2 and for Windows containers. | [optional]
**stats** | **array<string,int>** | All the stats exported via memory.stat. when using cgroups v2.  This field is Linux-specific and omitted for Windows containers. | [optional]
**failcnt** | **int** | Number of times memory usage hits limits.  This field is Linux-specific and only supported on cgroups v1. It is omitted when using cgroups v2 and for Windows containers. | [optional]
**limit** | **int** | This field is Linux-specific and omitted for Windows containers. | [optional]
**commitbytes** | **int** | Committed bytes.  This field is Windows-specific and omitted for Linux containers. | [optional]
**commitpeakbytes** | **int** | Peak committed bytes.  This field is Windows-specific and omitted for Linux containers. | [optional]
**privateworkingset** | **int** | Private working set.  This field is Windows-specific and omitted for Linux containers. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
