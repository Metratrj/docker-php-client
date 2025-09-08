# # OCIDescriptor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**media_type** | **string** | The media type of the object this schema refers to. | [optional]
**digest** | **string** | The digest of the targeted content. | [optional]
**size** | **int** | The size in bytes of the blob. | [optional]
**urls** | **string[]** | List of URLs from which this object MAY be downloaded. | [optional]
**annotations** | **array<string,string>** | Arbitrary metadata relating to the targeted content. | [optional]
**data** | **string** | Data is an embedding of the targeted content. This is encoded as a base64 string when marshalled to JSON (automatically, by encoding/json). If present, Data can be used directly to avoid fetching the targeted content. | [optional]
**platform** | [**\OpenAPI\Client\Model\OCIPlatform**](OCIPlatform.md) |  | [optional]
**artifact_type** | **string** | ArtifactType is the IANA media type of this artifact. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
