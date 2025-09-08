# # ImageManifestSummarySize

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** | Total is the total size (in bytes) of all the locally present data (both distributable and non-distributable) that&#39;s related to this manifest and its children. This equal to the sum of [Content] size AND all the sizes in the [Size] struct present in the Kind-specific data struct. For example, for an image kind (Kind &#x3D;&#x3D; \&quot;image\&quot;) this would include the size of the image content and unpacked image snapshots ([Size.Content] + [ImageData.Size.Unpacked]). |
**content** | **int** | Content is the size (in bytes) of all the locally present content in the content store (e.g. image config, layers) referenced by this manifest and its children. This only includes blobs in the content store. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
