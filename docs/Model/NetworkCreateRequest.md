# # NetworkCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | The network&#39;s name. |
**driver** | **string** | Name of the network driver plugin to use. | [optional] [default to 'bridge']
**scope** | **string** | The level at which the network exists (e.g. &#x60;swarm&#x60; for cluster-wide or &#x60;local&#x60; for machine level). | [optional]
**internal** | **bool** | Restrict external access to the network. | [optional]
**attachable** | **bool** | Globally scoped network is manually attachable by regular containers from workers in swarm mode. | [optional]
**ingress** | **bool** | Ingress network is the network which provides the routing-mesh in swarm mode. | [optional]
**config_only** | **bool** | Creates a config-only network. Config-only networks are placeholder networks for network configurations to be used by other networks. Config-only networks cannot be used directly to run containers or services. | [optional] [default to false]
**config_from** | [**\OpenAPI\Client\Model\ConfigReference**](ConfigReference.md) |  | [optional]
**ipam** | [**\OpenAPI\Client\Model\IPAM**](IPAM.md) |  | [optional]
**enable_ipv4** | **bool** | Enable IPv4 on the network. | [optional]
**enable_ipv6** | **bool** | Enable IPv6 on the network. | [optional]
**options** | **array<string,string>** | Network specific options to be used by the drivers. | [optional]
**labels** | **array<string,string>** | User-defined key/value metadata. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
