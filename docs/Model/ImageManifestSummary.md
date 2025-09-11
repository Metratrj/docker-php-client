# # ImageManifestSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | ID is the content-addressable ID of an image and is the same as the digest of the image manifest. |
**descriptor** | [**\OpenAPI\Client\Model\OCIDescriptor**](OCIDescriptor.md) |  |
**available** | **bool** | Indicates whether all the child content (image config, layers) is fully available locally. |
**size** | [**\OpenAPI\Client\Model\ImageManifestSummarySize**](ImageManifestSummarySize.md) |  |
**kind** | **string** | The kind of the manifest.  kind         | description -------------|----------------------------------------------------------- image        | Image manifest that can be used to start a container. attestation  | Attestation manifest produced by the Buildkit builder for a specific image manifest. |
**image_data** | [**\OpenAPI\Client\Model\ImageManifestSummaryImageData**](ImageManifestSummaryImageData.md) |  | [optional]
**attestation_data** | [**\OpenAPI\Client\Model\ImageManifestSummaryAttestationData**](ImageManifestSummaryAttestationData.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
