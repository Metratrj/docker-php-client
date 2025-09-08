# # ContainerSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | The ID of this container as a 128-bit (64-character) hexadecimal string (32 bytes). | [optional]
**names** | **string[]** | The names associated with this container. Most containers have a single name, but when using legacy \&quot;links\&quot;, the container can have multiple names.  For historic reasons, names are prefixed with a forward-slash (&#x60;/&#x60;). | [optional]
**image** | **string** | The name or ID of the image used to create the container.  This field shows the image reference as was specified when creating the container, which can be in its canonical form (e.g., &#x60;docker.io/library/ubuntu:latest&#x60; or &#x60;docker.io/library/ubuntu@sha256:72297848456d5d37d1262630108ab308d3e9ec7ed1c3286a32fe09856619a782&#x60;), short form (e.g., &#x60;ubuntu:latest&#x60;)), or the ID(-prefix) of the image (e.g., &#x60;72297848456d&#x60;).  The content of this field can be updated at runtime if the image used to create the container is untagged, in which case the field is updated to contain the the image ID (digest) it was resolved to in its canonical, non-truncated form (e.g., &#x60;sha256:72297848456d5d37d1262630108ab308d3e9ec7ed1c3286a32fe09856619a782&#x60;). | [optional]
**image_id** | **string** | The ID (digest) of the image that this container was created from. | [optional]
**image_manifest_descriptor** | [**\OpenAPI\Client\Model\OCIDescriptor**](OCIDescriptor.md) |  | [optional]
**command** | **string** | Command to run when starting the container | [optional]
**created** | **int** | Date and time at which the container was created as a Unix timestamp (number of seconds since EPOCH). | [optional]
**ports** | [**\OpenAPI\Client\Model\Port[]**](Port.md) | Port-mappings for the container. | [optional]
**size_rw** | **int** | The size of files that have been created or changed by this container.  This field is omitted by default, and only set when size is requested in the API request. | [optional]
**size_root_fs** | **int** | The total size of all files in the read-only layers from the image that the container uses. These layers can be shared between containers.  This field is omitted by default, and only set when size is requested in the API request. | [optional]
**labels** | **array<string,string>** | User-defined key/value metadata. | [optional]
**state** | **string** | The state of this container. | [optional]
**status** | **string** | Additional human-readable status of this container (e.g. &#x60;Exit 0&#x60;) | [optional]
**host_config** | [**\OpenAPI\Client\Model\ContainerSummaryHostConfig**](ContainerSummaryHostConfig.md) |  | [optional]
**network_settings** | [**\OpenAPI\Client\Model\ContainerSummaryNetworkSettings**](ContainerSummaryNetworkSettings.md) |  | [optional]
**mounts** | [**\OpenAPI\Client\Model\MountPoint[]**](MountPoint.md) | List of mounts used by the container. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
