# # ImageConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | **string** | The user that commands are run as inside the container. | [optional]
**exposed_ports** | **array<string,object>** | An object mapping ports to an empty object in the form:  &#x60;{\&quot;&lt;port&gt;/&lt;tcp|udp|sctp&gt;\&quot;: {}}&#x60; | [optional]
**env** | **string[]** | A list of environment variables to set inside the container in the form &#x60;[\&quot;VAR&#x3D;value\&quot;, ...]&#x60;. A variable without &#x60;&#x3D;&#x60; is removed from the environment, rather than to have an empty value. | [optional]
**cmd** | **string[]** | Command to run specified as a string or an array of strings. | [optional]
**healthcheck** | [**\OpenAPI\Client\Model\HealthConfig**](HealthConfig.md) |  | [optional]
**args_escaped** | **bool** | Command is already escaped (Windows only) | [optional] [default to false]
**volumes** | **array<string,object>** | An object mapping mount point paths inside the container to empty objects. | [optional]
**working_dir** | **string** | The working directory for commands to run in. | [optional]
**entrypoint** | **string[]** | The entry point for the container as a string or an array of strings.  If the array consists of exactly one empty string (&#x60;[\&quot;\&quot;]&#x60;) then the entry point is reset to system default (i.e., the entry point used by docker when there is no &#x60;ENTRYPOINT&#x60; instruction in the &#x60;Dockerfile&#x60;). | [optional]
**on_build** | **string[]** | &#x60;ONBUILD&#x60; metadata that were defined in the image&#39;s &#x60;Dockerfile&#x60;. | [optional]
**labels** | **array<string,string>** | User-defined key/value metadata. | [optional]
**stop_signal** | **string** | Signal to stop a container as a string or unsigned integer. | [optional]
**shell** | **string[]** | Shell for when &#x60;RUN&#x60;, &#x60;CMD&#x60;, and &#x60;ENTRYPOINT&#x60; uses a shell. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
