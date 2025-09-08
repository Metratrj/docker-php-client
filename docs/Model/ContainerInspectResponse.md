# # ContainerInspectResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | The ID of this container as a 128-bit (64-character) hexadecimal string (32 bytes). | [optional]
**created** | **string** | Date and time at which the container was created, formatted in [RFC 3339](https://www.ietf.org/rfc/rfc3339.txt) format with nano-seconds. | [optional]
**path** | **string** | The path to the command being run | [optional]
**args** | **string[]** | The arguments to the command being run | [optional]
**state** | [**\OpenAPI\Client\Model\ContainerState**](ContainerState.md) |  | [optional]
**image** | **string** | The ID (digest) of the image that this container was created from. | [optional]
**resolv_conf_path** | **string** | Location of the &#x60;/etc/resolv.conf&#x60; generated for the container on the host.  This file is managed through the docker daemon, and should not be accessed or modified by other tools. | [optional]
**hostname_path** | **string** | Location of the &#x60;/etc/hostname&#x60; generated for the container on the host.  This file is managed through the docker daemon, and should not be accessed or modified by other tools. | [optional]
**hosts_path** | **string** | Location of the &#x60;/etc/hosts&#x60; generated for the container on the host.  This file is managed through the docker daemon, and should not be accessed or modified by other tools. | [optional]
**log_path** | **string** | Location of the file used to buffer the container&#39;s logs. Depending on the logging-driver used for the container, this field may be omitted.  This file is managed through the docker daemon, and should not be accessed or modified by other tools. | [optional]
**name** | **string** | The name associated with this container.  For historic reasons, the name may be prefixed with a forward-slash (&#x60;/&#x60;). | [optional]
**restart_count** | **int** | Number of times the container was restarted since it was created, or since daemon was started. | [optional]
**driver** | **string** | The storage-driver used for the container&#39;s filesystem (graph-driver or snapshotter). | [optional]
**platform** | **string** | The platform (operating system) for which the container was created.  This field was introduced for the experimental \&quot;LCOW\&quot; (Linux Containers On Windows) features, which has been removed. In most cases, this field is equal to the host&#39;s operating system (&#x60;linux&#x60; or &#x60;windows&#x60;). | [optional]
**image_manifest_descriptor** | [**\OpenAPI\Client\Model\OCIDescriptor**](OCIDescriptor.md) |  | [optional]
**mount_label** | **string** | SELinux mount label set for the container. | [optional]
**process_label** | **string** | SELinux process label set for the container. | [optional]
**app_armor_profile** | **string** | The AppArmor profile set for the container. | [optional]
**exec_ids** | **string[]** | IDs of exec instances that are running in the container. | [optional]
**host_config** | [**\OpenAPI\Client\Model\HostConfig**](HostConfig.md) |  | [optional]
**graph_driver** | [**\OpenAPI\Client\Model\DriverData**](DriverData.md) |  | [optional]
**size_rw** | **int** | The size of files that have been created or changed by this container.  This field is omitted by default, and only set when size is requested in the API request. | [optional]
**size_root_fs** | **int** | The total size of all files in the read-only layers from the image that the container uses. These layers can be shared between containers.  This field is omitted by default, and only set when size is requested in the API request. | [optional]
**mounts** | [**\OpenAPI\Client\Model\MountPoint[]**](MountPoint.md) | List of mounts used by the container. | [optional]
**config** | [**\OpenAPI\Client\Model\ContainerConfig**](ContainerConfig.md) |  | [optional]
**network_settings** | [**\OpenAPI\Client\Model\NetworkSettings**](NetworkSettings.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
