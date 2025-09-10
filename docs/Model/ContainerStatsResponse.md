# # ContainerStatsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | Name of the container | [optional]
**id** | **string** | ID of the container | [optional]
**read** | **\DateTime** | Date and time at which this sample was collected. The value is formatted as [RFC 3339](https://www.ietf.org/rfc/rfc3339.txt) with nano-seconds. | [optional]
**preread** | **\DateTime** | Date and time at which this first sample was collected. This field is not propagated if the \&quot;one-shot\&quot; option is set. If the \&quot;one-shot\&quot; option is set, this field may be omitted, empty, or set to a default date (&#x60;0001-01-01T00:00:00Z&#x60;).  The value is formatted as [RFC 3339](https://www.ietf.org/rfc/rfc3339.txt) with nano-seconds. | [optional]
**pids_stats** | [**\OpenAPI\Client\Model\ContainerPidsStats**](ContainerPidsStats.md) |  | [optional]
**blkio_stats** | [**\OpenAPI\Client\Model\ContainerBlkioStats**](ContainerBlkioStats.md) |  | [optional]
**num_procs** | **int** | The number of processors on the system.  This field is Windows-specific and always zero for Linux containers. | [optional]
**storage_stats** | [**\OpenAPI\Client\Model\ContainerStorageStats**](ContainerStorageStats.md) |  | [optional]
**cpu_stats** | [**\OpenAPI\Client\Model\ContainerCPUStats**](ContainerCPUStats.md) |  | [optional]
**precpu_stats** | [**\OpenAPI\Client\Model\ContainerCPUStats**](ContainerCPUStats.md) |  | [optional]
**memory_stats** | [**\OpenAPI\Client\Model\ContainerMemoryStats**](ContainerMemoryStats.md) |  | [optional]
**networks** | **object** | Network statistics for the container per interface.  This field is omitted if the container has no networking enabled. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
