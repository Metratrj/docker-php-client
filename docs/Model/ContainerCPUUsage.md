# # ContainerCPUUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_usage** | **int** | Total CPU time consumed in nanoseconds (Linux) or 100&#39;s of nanoseconds (Windows). | [optional]
**percpu_usage** | **int[]** | Total CPU time (in nanoseconds) consumed per core (Linux).  This field is Linux-specific when using cgroups v1. It is omitted when using cgroups v2 and Windows containers. | [optional]
**usage_in_kernelmode** | **int** | Time (in nanoseconds) spent by tasks of the cgroup in kernel mode (Linux), or time spent (in 100&#39;s of nanoseconds) by all container processes in kernel mode (Windows).  Not populated for Windows containers using Hyper-V isolation. | [optional]
**usage_in_usermode** | **int** | Time (in nanoseconds) spent by tasks of the cgroup in user mode (Linux), or time spent (in 100&#39;s of nanoseconds) by all container processes in kernel mode (Windows).  Not populated for Windows containers using Hyper-V isolation. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
