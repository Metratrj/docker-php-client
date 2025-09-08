# # ContainerSummaryHostConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**network_mode** | **string** | Networking mode (&#x60;host&#x60;, &#x60;none&#x60;, &#x60;container:&lt;id&gt;&#x60;) or name of the primary network the container is using.  This field is primarily for backward compatibility. The container can be connected to multiple networks for which information can be found in the &#x60;NetworkSettings.Networks&#x60; field, which enumerates settings per network. | [optional]
**annotations** | **array<string,string>** | Arbitrary key-value metadata attached to the container. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
