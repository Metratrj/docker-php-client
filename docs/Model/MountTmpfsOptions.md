# # MountTmpfsOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**size_bytes** | **int** | The size for the tmpfs mount in bytes. | [optional]
**mode** | **int** | The permission mode for the tmpfs mount in an integer. | [optional]
**options** | **string[][]** | The options to be passed to the tmpfs mount. An array of arrays. Flag options should be provided as 1-length arrays. Other types should be provided as as 2-length arrays, where the first item is the key and the second the value. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
