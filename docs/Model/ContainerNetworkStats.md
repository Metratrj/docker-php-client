# # ContainerNetworkStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rx_bytes** | **int** | Bytes received. Windows and Linux. | [optional]
**rx_packets** | **int** | Packets received. Windows and Linux. | [optional]
**rx_errors** | **int** | Received errors. Not used on Windows.  This field is Linux-specific and always zero for Windows containers. | [optional]
**rx_dropped** | **int** | Incoming packets dropped. Windows and Linux. | [optional]
**tx_bytes** | **int** | Bytes sent. Windows and Linux. | [optional]
**tx_packets** | **int** | Packets sent. Windows and Linux. | [optional]
**tx_errors** | **int** | Sent errors. Not used on Windows.  This field is Linux-specific and always zero for Windows containers. | [optional]
**tx_dropped** | **int** | Outgoing packets dropped. Windows and Linux. | [optional]
**endpoint_id** | **string** | Endpoint ID. Not used on Linux.  This field is Windows-specific and omitted for Linux containers. | [optional]
**instance_id** | **string** | Instance ID. Not used on Linux.  This field is Windows-specific and omitted for Linux containers. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
