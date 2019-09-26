未指定 oos-templates 项目路径，使用 ../oos-templates 作为默认路径
####################################################################################################
# 拷贝 PublicTemplates 的模板到 ../oos-templates/PublicTemplates
####################################################################################################
处理 ACS-ECS-TagInstanceByRunCommandResult
处理 ACS-ECS-TagInstanceByOSType
处理 ACS-ECS-CloneInstancesAcrossRegion
处理 ACS-ECS-ScheduleToStopInstances
处理 ACS-ECS-ScheduleToRebootInstances
处理 ACS-ECS-ScheduleToUpgradeInternetBandwidth
处理 ACS-ECS-BulkyUpgradeInternetBandwidth
处理 ACS-ECS-BulkyTagInstanceByOSType
处理 ACS-ECS-BulkyDeletePrepaidInstances
处理 ACS-ECS-BulkyStopInstances
处理 ACS-ECS-RunInstancesWithApproval
处理 ACS-ECS-BulkyRebootInstances
处理 ACS-ECS-BulkyDeleteInstances
处理 ACS-ECS-BulkyInstallLogAgent
处理 ACS-ECS-RunShellScript
处理 ACS-ECS-CloneInstancesAcrossAZ
处理 ACS-ECS-ConvertsPublicIPToNewEIPByInstanceId
处理 ACS-ECS-ScheduleToStartInstances
处理 ACS-ECS-BulkyDeleteInstancesWithApproval
处理 ACS-ECS-BulkyStartInstances
处理 ACS-ECS-UpdateImage
处理 ACS-ESS-LifeCycleModifyMongoDBIPWhitelist
处理 ACS-ECS-BulkyTagInstanceByLinuxKernelVersion
处理 ACS-ESS-LifeCycleModifyRedisIPWhitelist
处理 ACS-ECS-RunRemoteShellScript
处理 ACS-ECS-TagInstanceByLinuxKernelVersion
处理 ACS-ECS-BulkyTagInstanceByRunCommandResult
处理 ACS-ECS-BulkyRunCommand
处理 ACS-InstallXDragonAndCloudMonitor
####################################################################################################
# 拷贝 CloudProductActions 的模板到 ../oos-templates/CloudProductActions
####################################################################################################
####################################################################################################
# 拷贝 CloudProductActions/DingTalk 的模板到 ../oos-templates/CloudProductActions/DingTalk
####################################################################################################
处理 ACS::Notify::DingTalkWebhook
处理 ACS::Approve::DingTalkWebhook
####################################################################################################
# 拷贝 CloudProductActions/FC 的模板到 ../oos-templates/CloudProductActions/FC
####################################################################################################
处理 ACS::FC::InvokeFunction
####################################################################################################
# 拷贝 CloudProductActions/ECS 的模板到 ../oos-templates/CloudProductActions/ECS
####################################################################################################
处理 ACS::ECS::InvokeCommand
处理 ACS::ECS::DescribeInstancesByTag
处理 ACS::ECS::DeleteImage
处理 ACS::ECS::ModifyVncPassword
处理 ACS::ECS::CreateImage
处理 ACS::ECS::ModifyInstanceVpcAttribute
处理 ACS::ECS::DeleteInstance
处理 ACS::ECS::StopInstance
处理 ACS::ECS::RunInstances
处理 ACS::ECS::DetachDisk
处理 ACS::ECS::InstallCloudAssistant
处理 ACS::ECS::AttachDisk
处理 ACS::ECS::CreateAndAttachDisk
处理 ACS::ECS::ModifyPrepaySpec
处理 ACS::ECS::CreateSnapshot
处理 ACS::ECS::ResetDisk
处理 ACS::ECS::RunCommand
处理 ACS::ECS::ResetPassword
处理 ACS::ECS::CopyLinuxInstanceFileFromOSS
处理 ACS::ECS::DescribeInstancesByName
处理 ACS::ECS::ReInitDisk
处理 ACS::ECS::StartInstance
处理 ACS::ECS::RebootInstance
处理 ACS::ECS::DescribeInstancesByStatus
处理 ACS::ECS::CopyLinuxInstanceFileToOSS
处理 ACS::ECS::ReplaceSystemDisk
处理 ACS::ECS::RunInstancesFromTemplate
处理 ACS::ECS::AllocatePublicIpAddress
处理 ACS::ECS::InstallLogtail
处理 ACS::ECS::CreateAndAttachNetworkInterface
处理 ACS::ECS::ResizeDisk
####################################################################################################
# 拷贝 CloudProductActions/RDC 的模板到 ../oos-templates/CloudProductActions/RDC
####################################################################################################
处理 ACS::RDC::RunCommand
####################################################################################################
# 拷贝 CloudProductActions/RDS 的模板到 ../oos-templates/CloudProductActions/RDS
####################################################################################################
处理 ACS::RDS::UpgradeDbInstanceEngineVersion
处理 ACS::RDS::DeleteDbInstance
处理 ACS::RDS::RecoveryDbInstance
处理 ACS::RDS::CreateDbInstance
处理 ACS::RDS::RestartDbInstance
处理 ACS::RDS::CreateDatabase
处理 ACS::RDS::CreateBackup

## 公共模板
| 序号   | 名称           | 描述（用途）                     | 链接         |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS-ECS-BulkyDeleteInstances | {'en': 'Bulky delete ECS postpaid instances.', 'zh-cn': '批量删除ECS按量付费实例。', 'name-en': 'ACS-ECS-BulkyDeleteInstances', 'name-zh-cn': '批量删除ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyDeleteInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyDeleteInstances.json) |
| 2 | ACS-ECS-BulkyDeleteInstancesWithApproval | {'en': 'Deletes the ECS postpaid instances with approval.', 'zh-cn': '通过审批后删除ECS按量付费实例。', 'name-en': 'ACS-ECS-BulkyDeleteInstancesWithApproval', 'name-zh-cn': '通过审批后批量删除ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyDeleteInstancesWithApproval.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyDeleteInstancesWithApproval.json) |
| 3 | ACS-ECS-BulkyDeletePrepaidInstances | {'en': 'Bulky delete prepaid instances.The specified ECS instances must be in stopped status.', 'zh-cn': '批量删除ECS预付费实例。指定的ECS实例必须处于已停止状态。', 'name-en': 'ACS-ECS-BulkyDeletePrepaidInstances', 'name-zh-cn': '批量删除ECS预付费实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyDeletePrepaidInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyDeletePrepaidInstances.json) |
| 4 | ACS-ECS-BulkyInstallLogAgent | {'en': 'Bulky installs SLS agent on ECS instance.', 'zh-cn': '批量在ECS实例上安装SLS代理。', 'name-en': 'ACS-ECS-BulkyInstallLogAgent', 'name-zh-cn': '批量安装SLS日志代理'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyInstallLogAgent.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyInstallLogAgent.json) |
| 5 | ACS-ECS-BulkyRebootInstances | {'en': 'Bulky restarts the ECS instances.', 'zh-cn': '批量重启ECS实例。', 'name-en': 'ACS-ECS-BulkyRebootInstances', 'name-zh-cn': '批量重启ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyRebootInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyRebootInstances.json) |
| 6 | ACS-ECS-BulkyRunCommand | {'en': 'Bulky run command on ECS instances.', 'zh-cn': '批量在多台ECS实例上运行云助手命令。', 'name-en': 'ACS-ECS-BulkyRunCommand', 'name-zh-cn': '批量在ECS实例上运行命令'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyRunCommand.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyRunCommand.json) |
| 7 | ACS-ECS-BulkyStartInstances | {'en': 'Bulky starts the ECS instances.', 'zh-cn': '批量启动ECS实例。', 'name-en': 'ACS-ECS-BulkyStartInstances', 'name-zh-cn': '批量启动ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyStartInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyStartInstances.json) |
| 8 | ACS-ECS-BulkyStopInstances | {'en': 'Bulky stops the ECS instances.', 'zh-cn': '批量停止ECS实例。', 'name-en': 'ACS-ECS-BulkyStopInstances', 'name-zh-cn': '批量停止ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyStopInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyStopInstances.json) |
| 9 | ACS-ECS-BulkyTagInstanceByLinuxKernelVersion | {'en': 'Bulky tag ECS instances using Linux kernel version as tag value by specifying instance IDs.', 'zh-cn': '批量通过指定实例IDs将Linux内核版本用作标记值标记ECS实例。', 'name-en': 'ACS-ECS-BulkyTagInstanceByLinuxKernelVersion', 'name-zh-cn': '批量根据Linux内核版本标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyTagInstanceByLinuxKernelVersion.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyTagInstanceByLinuxKernelVersion.json) |
| 10 | ACS-ECS-BulkyTagInstanceByOSType | {'en': 'Bulky tag ECS instances using OS type as tag value by specifying instance IDs.', 'zh-cn': '批量通过指定实例IDs将操作系统类型用作标记值标记ECS实例。', 'name-en': 'ACS-ECS-BulkyTagInstanceByOSType', 'name-zh-cn': '批量根据操作系统类型标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyTagInstanceByOSType.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyTagInstanceByOSType.json) |
| 11 | ACS-ECS-BulkyTagInstanceByRunCommandResult | {'en': 'Bulky tag ECS instances using RunCommand invocation result as tag value.', 'zh-cn': '批量根据运行云助手命令的结果标记实例。', 'name-en': 'ACS-ECS-BulkyTagInstanceByRunCommandResult', 'name-zh-cn': '批量根据运行命令的结果标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyTagInstanceByRunCommandResult.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyTagInstanceByRunCommandResult.json) |
| 12 | ACS-ECS-BulkyUpgradeInternetBandwidth | {'en': 'Bulky upgrades internet bandwidth of ECS instances.', 'zh-cn': '批量升级ECS实例公网带宽。', 'name-en': 'ACS-ECS-BulkyUpgradeInternetBandwidth', 'name-zh-cn': '批量升级ECS实例公网带宽'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyUpgradeInternetBandwidth.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyUpgradeInternetBandwidth.json) |
| 13 | ACS-ECS-CloneInstancesAcrossAZ | {'en': 'Cross available zone copy and run ECS instance of same InstanceType by InstanceIds.', 'zh-cn': '跨可用区克隆ECS实例。', 'name-en': 'ACS-ECS-CloneInstancesAcrossAZ', 'name-zh-cn': '跨可用区克隆ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-CloneInstancesAcrossAZ.yml) [JSON](PublicTemplates/JSON/ACS-ECS-CloneInstancesAcrossAZ.json) |
| 14 | ACS-ECS-CloneInstancesAcrossRegion | {'en': 'Cross Region copy and run ECS instance by InstanceIds.', 'zh-cn': '跨地域克隆ECS实例。', 'title': 'ACS-ECS-CloneInstancesAcrossRegion', 'name-zh-cn': '跨地域克隆ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-CloneInstancesAcrossRegion.yml) [JSON](PublicTemplates/JSON/ACS-ECS-CloneInstancesAcrossRegion.json) |
| 15 | ACS-ECS-ConvertsPublicIPToNewEIPByInstanceId | {'en': 'Converts the public IP address of a VPC-connected ECS instance with another Elastic IP (EIP) address.', 'zh-cn': '将一台网络类型为专有网络VPC的ECS实例的公网IP转化为其它弹性公网IP。', 'name-en': 'ACS-ECS-ConvertsPublicIPToNewEIPByInstanceId', 'name-zh-cn': '将一台实例的公网IP转化为其它弹性公网IP'} | [YAML](PublicTemplates/YAML/ACS-ECS-ConvertsPublicIPToNewEIPByInstanceId.yml) [JSON](PublicTemplates/JSON/ACS-ECS-ConvertsPublicIPToNewEIPByInstanceId.json) |
| 16 | ACS-ECS-RunInstancesWithApproval | {'en': 'Creates one or more ECS instances with approval.', 'zh-cn': '通过审批后创建ECS实例。', 'name-en': 'ACS-ECS-RunInstancesWithApproval', 'name-zh-cn': '通过审批后创建ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-RunInstancesWithApproval.yml) [JSON](PublicTemplates/JSON/ACS-ECS-RunInstancesWithApproval.json) |
| 17 | ACS-ECS-RunRemoteShellScript | {'en': 'Run remote shell script.', 'zh-cn': '运行远端shell脚本。', 'name-en': 'ACS-ECS-RunRemoteShellScript', 'name-zh-cn': '运行远端shell脚本'} | [YAML](PublicTemplates/YAML/ACS-ECS-RunRemoteShellScript.yml) [JSON](PublicTemplates/JSON/ACS-ECS-RunRemoteShellScript.json) |
| 18 | ACS-ECS-RunShellScript | {'en': 'Run shell script.', 'zh-cn': '运行shell脚本', 'title': 'ACS-ECS-RunShellScript', 'name-zh-cn': '运行shell脚本'} | [YAML](PublicTemplates/YAML/ACS-ECS-RunShellScript.yml) [JSON](PublicTemplates/JSON/ACS-ECS-RunShellScript.json) |
| 19 | ACS-ECS-ScheduleToRebootInstances | {'en': 'Schedules to reboot the ECS instances.', 'zh-cn': '定时重启ECS实例。', 'name-en': 'ACS-ECS-ScheduleToRebootInstances', 'name-zh-cn': '定时重启ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-ScheduleToRebootInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-ScheduleToRebootInstances.json) |
| 20 | ACS-ECS-ScheduleToStartInstances | {'en': 'Schedules to start the ECS instances.', 'zh-cn': '定时启动ECS实例。', 'name-en': 'ACS-ECS-ScheduleToStartInstances', 'name-zh-cn': '定时启动ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-ScheduleToStartInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-ScheduleToStartInstances.json) |
| 21 | ACS-ECS-ScheduleToStopInstances | {'en': 'Schedules to stop the ECS instances.', 'zh-cn': '定时停止ECS实例。', 'name-en': 'ACS-ECS-ScheduleToStopInstances', 'name-zh-cn': '定时停止ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-ScheduleToStopInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-ScheduleToStopInstances.json) |
| 22 | ACS-ECS-ScheduleToUpgradeInternetBandwidth | {'en': 'Schedules to upgrade internet bandwidth for ECS instances.', 'zh-cn': '定时升级ECS实例临时带宽。', 'name-en': 'ACS-ECS-ScheduleToUpgradeInternetBandwidth', 'name-zh-cn': '定时升级ECS实例临时带宽'} | [YAML](PublicTemplates/YAML/ACS-ECS-ScheduleToUpgradeInternetBandwidth.yml) [JSON](PublicTemplates/JSON/ACS-ECS-ScheduleToUpgradeInternetBandwidth.json) |
| 23 | ACS-ECS-TagInstanceByLinuxKernelVersion | {'en': 'Tag an ECS instance using Linux kernel version as tag value.', 'zh-cn': '通过Linux内核版本用作标记键标记一台ECS实例。', 'name-en': 'ACS-ECS-TagInstanceByLinuxKernelVersion', 'name-zh-cn': '批量根据Linux内核版本标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-TagInstanceByLinuxKernelVersion.yml) [JSON](PublicTemplates/JSON/ACS-ECS-TagInstanceByLinuxKernelVersion.json) |
| 24 | ACS-ECS-TagInstanceByOSType | {'en': 'Tag an ECS instance using OS type as tag value.', 'zh-cn': '将操作系统类型用作标记值标记一台ECS实例。', 'name-en': 'ACS-ECS-TagInstanceByOSType', 'name-zh-cn': '根据操作系统类型标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-TagInstanceByOSType.yml) [JSON](PublicTemplates/JSON/ACS-ECS-TagInstanceByOSType.json) |
| 25 | ACS-ECS-TagInstanceByRunCommandResult | {'en': 'Tag a Linux ECS using RunCommand invocation result as tag value.', 'zh-cn': '根据运行云助手命令的结果标记实例。', 'name-en': 'ACS-ECS-TagInstanceByRunCommandResult', 'name-zh-cn': '根据运行云助手命令的结果标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-TagInstanceByRunCommandResult.yml) [JSON](PublicTemplates/JSON/ACS-ECS-TagInstanceByRunCommandResult.json) |
| 26 | ACS-ECS-UpdateImage | {'en': 'Updates an existing ECS image via ECS Cloud Assistant then creates an ECS image.', 'zh-cn': '通过运行命令更新一个已存在的ECS镜像后创建一个新ECS镜像。', 'name-en': 'ACS-ECS-UpdateImage', 'name-zh-cn': '更新ECS镜像'} | [YAML](PublicTemplates/YAML/ACS-ECS-UpdateImage.yml) [JSON](PublicTemplates/JSON/ACS-ECS-UpdateImage.json) |
| 27 | ACS-ESS-LifeCycleModifyMongoDBIPWhitelist | {'en': 'Modify the wait state of the specified scaling activity according to the result of setting the IP whitelist of the MongoDB instance.', 'zh-cn': '根据设置MongoDB实例白名单结果修改伸缩活动的等待状态。', 'name-en': 'ACS-ESS-LifeCycleModifyMongoDBIPWhitelist', 'name-zh-cn': '弹性伸缩LifeCycleHook设置MongoDB白名单'} | [YAML](PublicTemplates/YAML/ACS-ESS-LifeCycleModifyMongoDBIPWhitelist.yml) [JSON](PublicTemplates/JSON/ACS-ESS-LifeCycleModifyMongoDBIPWhitelist.json) |
| 28 | ACS-ESS-LifeCycleModifyRedisIPWhitelist | {'en': 'Modify the wait state of the specified scaling activity according to the result of setting the IP whitelist of the MongoDB instance.', 'zh-cn': '根据设置Redis实例白名单结果修改伸缩活动的等待状态。', 'name-en': 'ACS-ESS-LifeCycleModifyRedisIPWhitelist', 'name-zh-cn': '弹性伸缩LifeCycleHook设置Redis白名单'} | [YAML](PublicTemplates/YAML/ACS-ESS-LifeCycleModifyRedisIPWhitelist.yml) [JSON](PublicTemplates/JSON/ACS-ESS-LifeCycleModifyRedisIPWhitelist.json) |
| 29 | ACS-InstallXDragonAndCloudMonitor | {'en': 'Bulky install XDragon hardware detection plug-in, cloud monitor, smartmontools, or uninstall and update XDragon hardware detection plug-in.', 'zh-cn': '批量安装神龙硬件检测插件、云监控、smartmontools,以及卸载与更新神龙硬件检测插件。', 'name-en': 'ACS-InstallXDragonAndCloudMonitor', 'name-zh-cn': '批量安装神龙监控插件'} | [YAML](PublicTemplates/YAML/ACS-InstallXDragonAndCloudMonitor.yml) [JSON](PublicTemplates/JSON/ACS-InstallXDragonAndCloudMonitor.json) |

## 云产品动作
### DingTalk
| 序号   | 名称           | 描述（用途）                     | 链接         |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS::Approve::DingTalkWebhook | Sends notification to DingTalk via webhook for asking approval. The execution remains paused until approved or rejected. Please refer https://open-doc.dingtalk.com/microapp/serverapi2/qf2nxq for details. | [YAML](CloudProductActions/DingTalk/YAML/ACS::Approve::DingTalkWebhook.yml) [JSON](CloudProductActions/DingTalk/JSON/ACS::Approve::DingTalkWebhook.json) |
| 2 | ACS::Notify::DingTalkWebhook | Sends notification to DingTalk via webhook. Please refer https://open-doc.dingtalk.com/microapp/serverapi2/qf2nxq for details. | [YAML](CloudProductActions/DingTalk/YAML/ACS::Notify::DingTalkWebhook.yml) [JSON](CloudProductActions/DingTalk/JSON/ACS::Notify::DingTalkWebhook.json) |

### ECS
| 序号   | 名称           | 描述（用途）                     | 链接         |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS::ECS::AllocatePublicIpAddress | Assigns a public IP address to an instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::AllocatePublicIpAddress.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::AllocatePublicIpAddress.json) |
| 2 | ACS::ECS::AttachDisk | Attaches a data disk to an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::AttachDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::AttachDisk.json) |
| 3 | ACS::ECS::CopyLinuxInstanceFileFromOSS | Copies the file from OSS to linux instance by RunCommand. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CopyLinuxInstanceFileFromOSS.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CopyLinuxInstanceFileFromOSS.json) |
| 4 | ACS::ECS::CopyLinuxInstanceFileToOSS | Copies the file from linux instance to OSS by RunCommand. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CopyLinuxInstanceFileToOSS.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CopyLinuxInstanceFileToOSS.json) |
| 5 | ACS::ECS::CreateAndAttachDisk | Creates a disk and attaches a data disk to an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CreateAndAttachDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CreateAndAttachDisk.json) |
| 6 | ACS::ECS::CreateAndAttachNetworkInterface | Creates an elastic network interface (ENI) and attaches to an instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CreateAndAttachNetworkInterface.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CreateAndAttachNetworkInterface.json) |
| 7 | ACS::ECS::CreateImage | Creates a custom image. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CreateImage.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CreateImage.json) |
| 8 | ACS::ECS::CreateSnapshot | Creates a snapshot for a disk. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CreateSnapshot.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CreateSnapshot.json) |
| 9 | ACS::ECS::DeleteImage | Deletes ECS image by specifying imageId. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DeleteImage.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DeleteImage.json) |
| 10 | ACS::ECS::DeleteInstance | Deletes ECS instance by specifying instance ID. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DeleteInstance.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DeleteInstance.json) |
| 11 | ACS::ECS::DescribeInstancesByName | Views the ECS instances by specifying instance name. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DescribeInstancesByName.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DescribeInstancesByName.json) |
| 12 | ACS::ECS::DescribeInstancesByStatus | Views the ECS instances by specifying instance status. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DescribeInstancesByStatus.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DescribeInstancesByStatus.json) |
| 13 | ACS::ECS::DescribeInstancesByTag | Views the ECS instances by specifying tag. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DescribeInstancesByTag.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DescribeInstancesByTag.json) |
| 14 | ACS::ECS::DetachDisk | Detaches a disk from an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DetachDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DetachDisk.json) |
| 15 | ACS::ECS::InstallCloudAssistant | Installs cloud assistant on ECS instance by specifying instanceId. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::InstallCloudAssistant.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::InstallCloudAssistant.json) |
| 16 | ACS::ECS::InstallLogtail | Installs SLS agent on ECS instance by running a cloud assistant command. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::InstallLogtail.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::InstallLogtail.json) |
| 17 | ACS::ECS::InvokeCommand | Triggers an exisiting cloud assistant command on one ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::InvokeCommand.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::InvokeCommand.json) |
| 18 | ACS::ECS::ModifyInstanceVpcAttribute | Modifies the VPC attributes of an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ModifyInstanceVpcAttribute.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ModifyInstanceVpcAttribute.json) |
| 19 | ACS::ECS::ModifyPrepaySpec | Changes the type of your subscription instance. The new instance type will take effect for the entire lifecycle of the instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ModifyPrepaySpec.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ModifyPrepaySpec.json) |
| 20 | ACS::ECS::ModifyVncPassword | Modifies the Web management terminal password of an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ModifyVncPassword.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ModifyVncPassword.json) |
| 21 | ACS::ECS::ReInitDisk | Resets a disk to its initial status.The specified ECS instances should be in stopped status. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ReInitDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ReInitDisk.json) |
| 22 | ACS::ECS::RebootInstance | Restarts the ECS instance by specifying instanceId. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::RebootInstance.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::RebootInstance.json) |
| 23 | ACS::ECS::ReplaceSystemDisk | Replaces the system disk of an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ReplaceSystemDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ReplaceSystemDisk.json) |
| 24 | ACS::ECS::ResetDisk | Rolls back a disk to the specific disk status by using one of its snapshots. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ResetDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ResetDisk.json) |
| 25 | ACS::ECS::ResetPassword | Resets password of an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ResetPassword.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ResetPassword.json) |
| 26 | ACS::ECS::ResizeDisk | Extends the size of a cloud disk. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ResizeDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ResizeDisk.json) |
| 27 | ACS::ECS::RunCommand | Creates a cloud assistant command and triggers it on one ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::RunCommand.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::RunCommand.json) |
| 28 | ACS::ECS::RunInstances | Creates one or more ECS instances. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::RunInstances.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::RunInstances.json) |
| 29 | ACS::ECS::RunInstancesFromTemplate | Creates one or more instances by specifying launch template. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::RunInstancesFromTemplate.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::RunInstancesFromTemplate.json) |
| 30 | ACS::ECS::StartInstance | Starts an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::StartInstance.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::StartInstance.json) |
| 31 | ACS::ECS::StopInstance | Stops an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::StopInstance.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::StopInstance.json) |

### FC
| 序号   | 名称           | 描述（用途）                     | 链接         |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS::FC::InvokeFunction | Invoke Created Function. | [YAML](CloudProductActions/FC/YAML/ACS::FC::InvokeFunction.yml) [JSON](CloudProductActions/FC/JSON/ACS::FC::InvokeFunction.json) |

### RDC
| 序号   | 名称           | 描述（用途）                     | 链接         |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS::RDC::RunCommand | Creates a cloud assistant command and triggers it on one ECS instance. | [YAML](CloudProductActions/RDC/YAML/ACS::RDC::RunCommand.yml) [JSON](CloudProductActions/RDC/JSON/ACS::RDC::RunCommand.json) |

### RDS
| 序号   | 名称           | 描述（用途）                     | 链接         |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS::RDS::CreateBackup | Creates backups of a RDS instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::CreateBackup.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::CreateBackup.json) |
| 2 | ACS::RDS::CreateDatabase | Creates a new database in an instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::CreateDatabase.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::CreateDatabase.json) |
| 3 | ACS::RDS::CreateDbInstance | Creates an RDS instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::CreateDbInstance.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::CreateDbInstance.json) |
| 4 | ACS::RDS::DeleteDbInstance | Deletes DB instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::DeleteDbInstance.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::DeleteDbInstance.json) |
| 5 | ACS::RDS::RecoveryDbInstance | Recoveries database to an existed or new instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::RecoveryDbInstance.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::RecoveryDbInstance.json) |
| 6 | ACS::RDS::RestartDbInstance | Restarts an RDS instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::RestartDbInstance.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::RestartDbInstance.json) |
| 7 | ACS::RDS::UpgradeDbInstanceEngineVersion | Upgrades the database version of an instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::UpgradeDbInstanceEngineVersion.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::UpgradeDbInstanceEngineVersion.json) |

## Public Templates
| No.   | Name           | Description                     | Links        |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS-ECS-BulkyDeleteInstances | {'en': 'Bulky delete ECS postpaid instances.', 'zh-cn': '批量删除ECS按量付费实例。', 'name-en': 'ACS-ECS-BulkyDeleteInstances', 'name-zh-cn': '批量删除ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyDeleteInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyDeleteInstances.json) |
| 2 | ACS-ECS-BulkyDeleteInstancesWithApproval | {'en': 'Deletes the ECS postpaid instances with approval.', 'zh-cn': '通过审批后删除ECS按量付费实例。', 'name-en': 'ACS-ECS-BulkyDeleteInstancesWithApproval', 'name-zh-cn': '通过审批后批量删除ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyDeleteInstancesWithApproval.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyDeleteInstancesWithApproval.json) |
| 3 | ACS-ECS-BulkyDeletePrepaidInstances | {'en': 'Bulky delete prepaid instances.The specified ECS instances must be in stopped status.', 'zh-cn': '批量删除ECS预付费实例。指定的ECS实例必须处于已停止状态。', 'name-en': 'ACS-ECS-BulkyDeletePrepaidInstances', 'name-zh-cn': '批量删除ECS预付费实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyDeletePrepaidInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyDeletePrepaidInstances.json) |
| 4 | ACS-ECS-BulkyInstallLogAgent | {'en': 'Bulky installs SLS agent on ECS instance.', 'zh-cn': '批量在ECS实例上安装SLS代理。', 'name-en': 'ACS-ECS-BulkyInstallLogAgent', 'name-zh-cn': '批量安装SLS日志代理'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyInstallLogAgent.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyInstallLogAgent.json) |
| 5 | ACS-ECS-BulkyRebootInstances | {'en': 'Bulky restarts the ECS instances.', 'zh-cn': '批量重启ECS实例。', 'name-en': 'ACS-ECS-BulkyRebootInstances', 'name-zh-cn': '批量重启ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyRebootInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyRebootInstances.json) |
| 6 | ACS-ECS-BulkyRunCommand | {'en': 'Bulky run command on ECS instances.', 'zh-cn': '批量在多台ECS实例上运行云助手命令。', 'name-en': 'ACS-ECS-BulkyRunCommand', 'name-zh-cn': '批量在ECS实例上运行命令'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyRunCommand.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyRunCommand.json) |
| 7 | ACS-ECS-BulkyStartInstances | {'en': 'Bulky starts the ECS instances.', 'zh-cn': '批量启动ECS实例。', 'name-en': 'ACS-ECS-BulkyStartInstances', 'name-zh-cn': '批量启动ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyStartInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyStartInstances.json) |
| 8 | ACS-ECS-BulkyStopInstances | {'en': 'Bulky stops the ECS instances.', 'zh-cn': '批量停止ECS实例。', 'name-en': 'ACS-ECS-BulkyStopInstances', 'name-zh-cn': '批量停止ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyStopInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyStopInstances.json) |
| 9 | ACS-ECS-BulkyTagInstanceByLinuxKernelVersion | {'en': 'Bulky tag ECS instances using Linux kernel version as tag value by specifying instance IDs.', 'zh-cn': '批量通过指定实例IDs将Linux内核版本用作标记值标记ECS实例。', 'name-en': 'ACS-ECS-BulkyTagInstanceByLinuxKernelVersion', 'name-zh-cn': '批量根据Linux内核版本标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyTagInstanceByLinuxKernelVersion.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyTagInstanceByLinuxKernelVersion.json) |
| 10 | ACS-ECS-BulkyTagInstanceByOSType | {'en': 'Bulky tag ECS instances using OS type as tag value by specifying instance IDs.', 'zh-cn': '批量通过指定实例IDs将操作系统类型用作标记值标记ECS实例。', 'name-en': 'ACS-ECS-BulkyTagInstanceByOSType', 'name-zh-cn': '批量根据操作系统类型标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyTagInstanceByOSType.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyTagInstanceByOSType.json) |
| 11 | ACS-ECS-BulkyTagInstanceByRunCommandResult | {'en': 'Bulky tag ECS instances using RunCommand invocation result as tag value.', 'zh-cn': '批量根据运行云助手命令的结果标记实例。', 'name-en': 'ACS-ECS-BulkyTagInstanceByRunCommandResult', 'name-zh-cn': '批量根据运行命令的结果标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyTagInstanceByRunCommandResult.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyTagInstanceByRunCommandResult.json) |
| 12 | ACS-ECS-BulkyUpgradeInternetBandwidth | {'en': 'Bulky upgrades internet bandwidth of ECS instances.', 'zh-cn': '批量升级ECS实例公网带宽。', 'name-en': 'ACS-ECS-BulkyUpgradeInternetBandwidth', 'name-zh-cn': '批量升级ECS实例公网带宽'} | [YAML](PublicTemplates/YAML/ACS-ECS-BulkyUpgradeInternetBandwidth.yml) [JSON](PublicTemplates/JSON/ACS-ECS-BulkyUpgradeInternetBandwidth.json) |
| 13 | ACS-ECS-CloneInstancesAcrossAZ | {'en': 'Cross available zone copy and run ECS instance of same InstanceType by InstanceIds.', 'zh-cn': '跨可用区克隆ECS实例。', 'name-en': 'ACS-ECS-CloneInstancesAcrossAZ', 'name-zh-cn': '跨可用区克隆ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-CloneInstancesAcrossAZ.yml) [JSON](PublicTemplates/JSON/ACS-ECS-CloneInstancesAcrossAZ.json) |
| 14 | ACS-ECS-CloneInstancesAcrossRegion | {'en': 'Cross Region copy and run ECS instance by InstanceIds.', 'zh-cn': '跨地域克隆ECS实例。', 'title': 'ACS-ECS-CloneInstancesAcrossRegion', 'name-zh-cn': '跨地域克隆ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-CloneInstancesAcrossRegion.yml) [JSON](PublicTemplates/JSON/ACS-ECS-CloneInstancesAcrossRegion.json) |
| 15 | ACS-ECS-ConvertsPublicIPToNewEIPByInstanceId | {'en': 'Converts the public IP address of a VPC-connected ECS instance with another Elastic IP (EIP) address.', 'zh-cn': '将一台网络类型为专有网络VPC的ECS实例的公网IP转化为其它弹性公网IP。', 'name-en': 'ACS-ECS-ConvertsPublicIPToNewEIPByInstanceId', 'name-zh-cn': '将一台实例的公网IP转化为其它弹性公网IP'} | [YAML](PublicTemplates/YAML/ACS-ECS-ConvertsPublicIPToNewEIPByInstanceId.yml) [JSON](PublicTemplates/JSON/ACS-ECS-ConvertsPublicIPToNewEIPByInstanceId.json) |
| 16 | ACS-ECS-RunInstancesWithApproval | {'en': 'Creates one or more ECS instances with approval.', 'zh-cn': '通过审批后创建ECS实例。', 'name-en': 'ACS-ECS-RunInstancesWithApproval', 'name-zh-cn': '通过审批后创建ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-RunInstancesWithApproval.yml) [JSON](PublicTemplates/JSON/ACS-ECS-RunInstancesWithApproval.json) |
| 17 | ACS-ECS-RunRemoteShellScript | {'en': 'Run remote shell script.', 'zh-cn': '运行远端shell脚本。', 'name-en': 'ACS-ECS-RunRemoteShellScript', 'name-zh-cn': '运行远端shell脚本'} | [YAML](PublicTemplates/YAML/ACS-ECS-RunRemoteShellScript.yml) [JSON](PublicTemplates/JSON/ACS-ECS-RunRemoteShellScript.json) |
| 18 | ACS-ECS-RunShellScript | {'en': 'Run shell script.', 'zh-cn': '运行shell脚本', 'title': 'ACS-ECS-RunShellScript', 'name-zh-cn': '运行shell脚本'} | [YAML](PublicTemplates/YAML/ACS-ECS-RunShellScript.yml) [JSON](PublicTemplates/JSON/ACS-ECS-RunShellScript.json) |
| 19 | ACS-ECS-ScheduleToRebootInstances | {'en': 'Schedules to reboot the ECS instances.', 'zh-cn': '定时重启ECS实例。', 'name-en': 'ACS-ECS-ScheduleToRebootInstances', 'name-zh-cn': '定时重启ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-ScheduleToRebootInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-ScheduleToRebootInstances.json) |
| 20 | ACS-ECS-ScheduleToStartInstances | {'en': 'Schedules to start the ECS instances.', 'zh-cn': '定时启动ECS实例。', 'name-en': 'ACS-ECS-ScheduleToStartInstances', 'name-zh-cn': '定时启动ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-ScheduleToStartInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-ScheduleToStartInstances.json) |
| 21 | ACS-ECS-ScheduleToStopInstances | {'en': 'Schedules to stop the ECS instances.', 'zh-cn': '定时停止ECS实例。', 'name-en': 'ACS-ECS-ScheduleToStopInstances', 'name-zh-cn': '定时停止ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-ScheduleToStopInstances.yml) [JSON](PublicTemplates/JSON/ACS-ECS-ScheduleToStopInstances.json) |
| 22 | ACS-ECS-ScheduleToUpgradeInternetBandwidth | {'en': 'Schedules to upgrade internet bandwidth for ECS instances.', 'zh-cn': '定时升级ECS实例临时带宽。', 'name-en': 'ACS-ECS-ScheduleToUpgradeInternetBandwidth', 'name-zh-cn': '定时升级ECS实例临时带宽'} | [YAML](PublicTemplates/YAML/ACS-ECS-ScheduleToUpgradeInternetBandwidth.yml) [JSON](PublicTemplates/JSON/ACS-ECS-ScheduleToUpgradeInternetBandwidth.json) |
| 23 | ACS-ECS-TagInstanceByLinuxKernelVersion | {'en': 'Tag an ECS instance using Linux kernel version as tag value.', 'zh-cn': '通过Linux内核版本用作标记键标记一台ECS实例。', 'name-en': 'ACS-ECS-TagInstanceByLinuxKernelVersion', 'name-zh-cn': '批量根据Linux内核版本标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-TagInstanceByLinuxKernelVersion.yml) [JSON](PublicTemplates/JSON/ACS-ECS-TagInstanceByLinuxKernelVersion.json) |
| 24 | ACS-ECS-TagInstanceByOSType | {'en': 'Tag an ECS instance using OS type as tag value.', 'zh-cn': '将操作系统类型用作标记值标记一台ECS实例。', 'name-en': 'ACS-ECS-TagInstanceByOSType', 'name-zh-cn': '根据操作系统类型标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-TagInstanceByOSType.yml) [JSON](PublicTemplates/JSON/ACS-ECS-TagInstanceByOSType.json) |
| 25 | ACS-ECS-TagInstanceByRunCommandResult | {'en': 'Tag a Linux ECS using RunCommand invocation result as tag value.', 'zh-cn': '根据运行云助手命令的结果标记实例。', 'name-en': 'ACS-ECS-TagInstanceByRunCommandResult', 'name-zh-cn': '根据运行云助手命令的结果标记ECS实例'} | [YAML](PublicTemplates/YAML/ACS-ECS-TagInstanceByRunCommandResult.yml) [JSON](PublicTemplates/JSON/ACS-ECS-TagInstanceByRunCommandResult.json) |
| 26 | ACS-ECS-UpdateImage | {'en': 'Updates an existing ECS image via ECS Cloud Assistant then creates an ECS image.', 'zh-cn': '通过运行命令更新一个已存在的ECS镜像后创建一个新ECS镜像。', 'name-en': 'ACS-ECS-UpdateImage', 'name-zh-cn': '更新ECS镜像'} | [YAML](PublicTemplates/YAML/ACS-ECS-UpdateImage.yml) [JSON](PublicTemplates/JSON/ACS-ECS-UpdateImage.json) |
| 27 | ACS-ESS-LifeCycleModifyMongoDBIPWhitelist | {'en': 'Modify the wait state of the specified scaling activity according to the result of setting the IP whitelist of the MongoDB instance.', 'zh-cn': '根据设置MongoDB实例白名单结果修改伸缩活动的等待状态。', 'name-en': 'ACS-ESS-LifeCycleModifyMongoDBIPWhitelist', 'name-zh-cn': '弹性伸缩LifeCycleHook设置MongoDB白名单'} | [YAML](PublicTemplates/YAML/ACS-ESS-LifeCycleModifyMongoDBIPWhitelist.yml) [JSON](PublicTemplates/JSON/ACS-ESS-LifeCycleModifyMongoDBIPWhitelist.json) |
| 28 | ACS-ESS-LifeCycleModifyRedisIPWhitelist | {'en': 'Modify the wait state of the specified scaling activity according to the result of setting the IP whitelist of the MongoDB instance.', 'zh-cn': '根据设置Redis实例白名单结果修改伸缩活动的等待状态。', 'name-en': 'ACS-ESS-LifeCycleModifyRedisIPWhitelist', 'name-zh-cn': '弹性伸缩LifeCycleHook设置Redis白名单'} | [YAML](PublicTemplates/YAML/ACS-ESS-LifeCycleModifyRedisIPWhitelist.yml) [JSON](PublicTemplates/JSON/ACS-ESS-LifeCycleModifyRedisIPWhitelist.json) |
| 29 | ACS-InstallXDragonAndCloudMonitor | {'en': 'Bulky install XDragon hardware detection plug-in, cloud monitor, smartmontools, or uninstall and update XDragon hardware detection plug-in.', 'zh-cn': '批量安装神龙硬件检测插件、云监控、smartmontools,以及卸载与更新神龙硬件检测插件。', 'name-en': 'ACS-InstallXDragonAndCloudMonitor', 'name-zh-cn': '批量安装神龙监控插件'} | [YAML](PublicTemplates/YAML/ACS-InstallXDragonAndCloudMonitor.yml) [JSON](PublicTemplates/JSON/ACS-InstallXDragonAndCloudMonitor.json) |

## Cloud Product Actions
### DingTalk
| No.   | Name           | Description                     | Links        |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS::Approve::DingTalkWebhook | Sends notification to DingTalk via webhook for asking approval. The execution remains paused until approved or rejected. Please refer https://open-doc.dingtalk.com/microapp/serverapi2/qf2nxq for details. | [YAML](CloudProductActions/DingTalk/YAML/ACS::Approve::DingTalkWebhook.yml) [JSON](CloudProductActions/DingTalk/JSON/ACS::Approve::DingTalkWebhook.json) |
| 2 | ACS::Notify::DingTalkWebhook | Sends notification to DingTalk via webhook. Please refer https://open-doc.dingtalk.com/microapp/serverapi2/qf2nxq for details. | [YAML](CloudProductActions/DingTalk/YAML/ACS::Notify::DingTalkWebhook.yml) [JSON](CloudProductActions/DingTalk/JSON/ACS::Notify::DingTalkWebhook.json) |

### ECS
| No.   | Name           | Description                     | Links        |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS::ECS::AllocatePublicIpAddress | Assigns a public IP address to an instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::AllocatePublicIpAddress.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::AllocatePublicIpAddress.json) |
| 2 | ACS::ECS::AttachDisk | Attaches a data disk to an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::AttachDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::AttachDisk.json) |
| 3 | ACS::ECS::CopyLinuxInstanceFileFromOSS | Copies the file from OSS to linux instance by RunCommand. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CopyLinuxInstanceFileFromOSS.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CopyLinuxInstanceFileFromOSS.json) |
| 4 | ACS::ECS::CopyLinuxInstanceFileToOSS | Copies the file from linux instance to OSS by RunCommand. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CopyLinuxInstanceFileToOSS.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CopyLinuxInstanceFileToOSS.json) |
| 5 | ACS::ECS::CreateAndAttachDisk | Creates a disk and attaches a data disk to an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CreateAndAttachDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CreateAndAttachDisk.json) |
| 6 | ACS::ECS::CreateAndAttachNetworkInterface | Creates an elastic network interface (ENI) and attaches to an instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CreateAndAttachNetworkInterface.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CreateAndAttachNetworkInterface.json) |
| 7 | ACS::ECS::CreateImage | Creates a custom image. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CreateImage.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CreateImage.json) |
| 8 | ACS::ECS::CreateSnapshot | Creates a snapshot for a disk. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::CreateSnapshot.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::CreateSnapshot.json) |
| 9 | ACS::ECS::DeleteImage | Deletes ECS image by specifying imageId. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DeleteImage.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DeleteImage.json) |
| 10 | ACS::ECS::DeleteInstance | Deletes ECS instance by specifying instance ID. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DeleteInstance.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DeleteInstance.json) |
| 11 | ACS::ECS::DescribeInstancesByName | Views the ECS instances by specifying instance name. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DescribeInstancesByName.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DescribeInstancesByName.json) |
| 12 | ACS::ECS::DescribeInstancesByStatus | Views the ECS instances by specifying instance status. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DescribeInstancesByStatus.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DescribeInstancesByStatus.json) |
| 13 | ACS::ECS::DescribeInstancesByTag | Views the ECS instances by specifying tag. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DescribeInstancesByTag.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DescribeInstancesByTag.json) |
| 14 | ACS::ECS::DetachDisk | Detaches a disk from an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::DetachDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::DetachDisk.json) |
| 15 | ACS::ECS::InstallCloudAssistant | Installs cloud assistant on ECS instance by specifying instanceId. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::InstallCloudAssistant.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::InstallCloudAssistant.json) |
| 16 | ACS::ECS::InstallLogtail | Installs SLS agent on ECS instance by running a cloud assistant command. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::InstallLogtail.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::InstallLogtail.json) |
| 17 | ACS::ECS::InvokeCommand | Triggers an exisiting cloud assistant command on one ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::InvokeCommand.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::InvokeCommand.json) |
| 18 | ACS::ECS::ModifyInstanceVpcAttribute | Modifies the VPC attributes of an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ModifyInstanceVpcAttribute.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ModifyInstanceVpcAttribute.json) |
| 19 | ACS::ECS::ModifyPrepaySpec | Changes the type of your subscription instance. The new instance type will take effect for the entire lifecycle of the instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ModifyPrepaySpec.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ModifyPrepaySpec.json) |
| 20 | ACS::ECS::ModifyVncPassword | Modifies the Web management terminal password of an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ModifyVncPassword.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ModifyVncPassword.json) |
| 21 | ACS::ECS::ReInitDisk | Resets a disk to its initial status.The specified ECS instances should be in stopped status. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ReInitDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ReInitDisk.json) |
| 22 | ACS::ECS::RebootInstance | Restarts the ECS instance by specifying instanceId. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::RebootInstance.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::RebootInstance.json) |
| 23 | ACS::ECS::ReplaceSystemDisk | Replaces the system disk of an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ReplaceSystemDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ReplaceSystemDisk.json) |
| 24 | ACS::ECS::ResetDisk | Rolls back a disk to the specific disk status by using one of its snapshots. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ResetDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ResetDisk.json) |
| 25 | ACS::ECS::ResetPassword | Resets password of an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ResetPassword.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ResetPassword.json) |
| 26 | ACS::ECS::ResizeDisk | Extends the size of a cloud disk. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::ResizeDisk.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::ResizeDisk.json) |
| 27 | ACS::ECS::RunCommand | Creates a cloud assistant command and triggers it on one ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::RunCommand.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::RunCommand.json) |
| 28 | ACS::ECS::RunInstances | Creates one or more ECS instances. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::RunInstances.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::RunInstances.json) |
| 29 | ACS::ECS::RunInstancesFromTemplate | Creates one or more instances by specifying launch template. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::RunInstancesFromTemplate.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::RunInstancesFromTemplate.json) |
| 30 | ACS::ECS::StartInstance | Starts an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::StartInstance.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::StartInstance.json) |
| 31 | ACS::ECS::StopInstance | Stops an ECS instance. | [YAML](CloudProductActions/ECS/YAML/ACS::ECS::StopInstance.yml) [JSON](CloudProductActions/ECS/JSON/ACS::ECS::StopInstance.json) |

### FC
| No.   | Name           | Description                     | Links        |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS::FC::InvokeFunction | Invoke Created Function. | [YAML](CloudProductActions/FC/YAML/ACS::FC::InvokeFunction.yml) [JSON](CloudProductActions/FC/JSON/ACS::FC::InvokeFunction.json) |

### RDC
| No.   | Name           | Description                     | Links        |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS::RDC::RunCommand | Creates a cloud assistant command and triggers it on one ECS instance. | [YAML](CloudProductActions/RDC/YAML/ACS::RDC::RunCommand.yml) [JSON](CloudProductActions/RDC/JSON/ACS::RDC::RunCommand.json) |

### RDS
| No.   | Name           | Description                     | Links        |
| ----- | -------------- | ------------------------------- | ------------ |
| 1 | ACS::RDS::CreateBackup | Creates backups of a RDS instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::CreateBackup.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::CreateBackup.json) |
| 2 | ACS::RDS::CreateDatabase | Creates a new database in an instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::CreateDatabase.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::CreateDatabase.json) |
| 3 | ACS::RDS::CreateDbInstance | Creates an RDS instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::CreateDbInstance.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::CreateDbInstance.json) |
| 4 | ACS::RDS::DeleteDbInstance | Deletes DB instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::DeleteDbInstance.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::DeleteDbInstance.json) |
| 5 | ACS::RDS::RecoveryDbInstance | Recoveries database to an existed or new instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::RecoveryDbInstance.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::RecoveryDbInstance.json) |
| 6 | ACS::RDS::RestartDbInstance | Restarts an RDS instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::RestartDbInstance.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::RestartDbInstance.json) |
| 7 | ACS::RDS::UpgradeDbInstanceEngineVersion | Upgrades the database version of an instance. | [YAML](CloudProductActions/RDS/YAML/ACS::RDS::UpgradeDbInstanceEngineVersion.yml) [JSON](CloudProductActions/RDS/JSON/ACS::RDS::UpgradeDbInstanceEngineVersion.json) |
