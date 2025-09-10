# # Network

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | Name of the network. | [optional]
**id** | **string** | ID that uniquely identifies a network on a single machine. | [optional]
**created** | **string** | Date and time at which the network was created in [RFC 3339](https://www.ietf.org/rfc/rfc3339.txt) format with nano-seconds. | [optional]
**scope** | **string** | The level at which the network exists (e.g. &#x60;swarm&#x60; for cluster-wide or &#x60;local&#x60; for machine level) | [optional]
**driver** | **string** | The name of the driver used to create the network (e.g. &#x60;bridge&#x60;, &#x60;overlay&#x60;). | [optional]
**enable_ipv4** | **bool** | Whether the network was created with IPv4 enabled. | [optional]
**enable_ipv6** | **bool** | Whether the network was created with IPv6 enabled. | [optional]
**ipam** | [**\OpenAPI\Client\Model\IPAM**](IPAM.md) |  | [optional]
**internal** | **bool** | Whether the network is created to only allow internal networking connectivity. | [optional] [default to false]
**attachable** | **bool** | Whether a global / swarm scope network is manually attachable by regular containers from workers in swarm mode. | [optional] [default to false]
**ingress** | **bool** | Whether the network is providing the routing-mesh for the swarm cluster. | [optional] [default to false]
**config_from** | [**\OpenAPI\Client\Model\ConfigReference**](ConfigReference.md) |  | [optional]
**config_only** | **bool** | Whether the network is a config-only network. Config-only networks are placeholder networks for network configurations to be used by other networks. Config-only networks cannot be used directly to run containers or services. | [optional] [default to false]
**containers** | [**array<string,\OpenAPI\Client\Model\NetworkContainer>**](NetworkContainer.md) | Contains endpoints attached to the network. | [optional]
**options** | **array<string,string>** | Network-specific options uses when creating the network. | [optional]
**labels** | **array<string,string>** | User-defined key/value metadata. | [optional]
**peers** | [**\OpenAPI\Client\Model\PeerInfo[]**](PeerInfo.md) | List of peer nodes for an overlay network. This field is only present for overlay networks, and omitted for other network types. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
