/workspaces $ npx n8n

Need to install the following packages:
n8n@1.78.1
Ok to proceed? (y) 
(########⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠦ idealTree:https-proxy-agent: timing idealTree:node_modules/gaxios/node_modules/

/workspaces $ pnpm build
 ERR_PNPM_NO_IMPORTER_MANIFEST_FOUND  No package.json (or package.yaml, or package.json5) was found in "/workspaces".
/workspaces $ npx n8n

Need to install the following packages:
n8n@1.78.1
Ok to proceed? (y) 
npm WARN deprecated inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
npm WARN deprecated are-we-there-yet@3.0.1: This package is no longer supported.
npm WARN deprecated @npmcli/move-file@1.1.2: This functionality has been moved to @npmcli/fs
npm WARN deprecated npmlog@6.0.2: This package is no longer supported.
npm WARN deprecated rimraf@3.0.2: Rimraf versions prior to v4 are no longer supported
npm WARN deprecated @aws-sdk/node-http-handler@3.374.0: This package has moved to @smithy/node-http-handler
npm WARN deprecated gauge@4.0.4: This package is no longer supported.
npm WARN deprecated dommatrix@1.0.3: dommatrix is no longer maintained. Please use @thednp/dommatrix.
npm WARN deprecated google-p12-pem@4.0.1: Package is no longer maintained
npm WARN deprecated lodash.get@4.4.2: This package is deprecated. Use the optional chaining (?.) operator instead.
npm WARN deprecated @aws-sdk/signature-v4@3.374.0: This package has moved to @smithy/signature-v4
npm WARN deprecated @aws-sdk/protocol-http@3.374.0: This package has moved to @smithy/protocol-http
npm WARN deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm WARN deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm WARN deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm WARN deprecated rimraf@2.6.3: Rimraf versions prior to v4 are no longer supported
npm WARN deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm WARN deprecated infisical-node@1.3.0: Package no longer supported. Contact Support at https://www.npmjs.com/support for more info.
npm WARN deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm WARN deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
(#################⠂) ⠙ reify:uuid: http fetch GET 200(#################⠂) ⠹ reify:@smithy/middleware-retry(#################⠂) ⠸ reify:@smithy/middleware-retry(#################⠂) ⠴ reify:@smithy/util-stream: tim(#################⠂) ⠋ reify:@smithy/config-resolver:(#################⠂) ⠧ reify:@aws-sdk/types: timing r
npm WARN deprecated @azure/core-http@3.0.5: This package is no longer supported. Please refer to https://github.com/Azure/azure-sdk-for-js/blob/490ce4dfc5b98ba290dee3b33a6d0876c5f138e2/sdk/core/README.md
No encryption key found - Auto-generated and saved to: /home/node/.n8n/config
Permissions 0644 for n8n settings file /home/node/.n8n/config are too wide. This is ignored for now, but in the future n8n will attempt to change the permissions automatically. To automatically enforce correct permissions now set N8N_ENFORCE_SETTINGS_FILE_PERMISSIONS=true (recommended), or turn this check off set N8N_ENFORCE_SETTINGS_FILE_PERMISSIONS=false.
Initializing n8n process
n8n ready on 0.0.0.0, port 5678
Migrations in progress, please do NOT stop the process.
Starting migration InitialMigration1587669153312
Finished migration InitialMigration1587669153312
Starting migration WebhookModel1589476000887
Finished migration WebhookModel1589476000887
Starting migration CreateIndexStoppedAt1594828256133
Finished migration CreateIndexStoppedAt1594828256133
Starting migration MakeStoppedAtNullable1607431743768
Finished migration MakeStoppedAtNullable1607431743768
Starting migration AddWebhookId1611144599516
Finished migration AddWebhookId1611144599516
Starting migration CreateTagEntity1617270242566
Finished migration CreateTagEntity1617270242566
Starting migration UniqueWorkflowNames1620824779533
Finished migration UniqueWorkflowNames1620824779533
Starting migration AddwaitTill1626176912946
Finished migration AddwaitTill1626176912946
Starting migration UpdateWorkflowCredentials1630419189837
Finished migration UpdateWorkflowCredentials1630419189837
Starting migration AddExecutionEntityIndexes1644422880309
Finished migration AddExecutionEntityIndexes1644422880309
Starting migration IncreaseTypeVarcharLimit1646834195327
Finished migration IncreaseTypeVarcharLimit1646834195327
Starting migration CreateUserManagement1646992772331
Finished migration CreateUserManagement1646992772331
Starting migration LowerCaseUserEmail1648740597343
Finished migration LowerCaseUserEmail1648740597343
Starting migration CommunityNodes1652254514002
Finished migration CommunityNodes1652254514002
Starting migration AddUserSettings1652367743993
Finished migration AddUserSettings1652367743993
Starting migration AddAPIKeyColumn1652905585850
Finished migration AddAPIKeyColumn1652905585850
Starting migration IntroducePinData1654090467022
Finished migration IntroducePinData1654090467022
Starting migration AddNodeIds1658932090381
Finished migration AddNodeIds1658932090381
Starting migration AddJsonKeyPinData1659902242948
Finished migration AddJsonKeyPinData1659902242948
Starting migration CreateCredentialsUserRole1660062385367
Finished migration CreateCredentialsUserRole1660062385367
Starting migration CreateWorkflowsEditorRole1663755770893
Finished migration CreateWorkflowsEditorRole1663755770893
Starting migration WorkflowStatistics1664196174001
Finished migration WorkflowStatistics1664196174001
Starting migration CreateCredentialUsageTable1665484192212
Finished migration CreateCredentialUsageTable1665484192212
Starting migration RemoveCredentialUsageTable1665754637025
Finished migration RemoveCredentialUsageTable1665754637025
Starting migration AddWorkflowVersionIdColumn1669739707126
Finished migration AddWorkflowVersionIdColumn1669739707126
Starting migration AddTriggerCountColumn1669823906995
Finished migration AddTriggerCountColumn1669823906995
Starting migration MessageEventBusDestinations1671535397530
Finished migration MessageEventBusDestinations1671535397530
Starting migration RemoveWorkflowDataLoadedFlag1671726148421
Finished migration RemoveWorkflowDataLoadedFlag1671726148421
Starting migration DeleteExecutionsWithWorkflows1673268682475
Finished migration DeleteExecutionsWithWorkflows1673268682475
Starting migration AddStatusToExecutions1674138566000
Finished migration AddStatusToExecutions1674138566000
Starting migration CreateLdapEntities1674509946020
Finished migration CreateLdapEntities1674509946020
Starting migration PurgeInvalidWorkflowConnections1675940580449
Finished migration PurgeInvalidWorkflowConnections1675940580449
Starting migration MigrateExecutionStatus1676996103000
Finished migration MigrateExecutionStatus1676996103000
Starting migration UpdateRunningExecutionStatus1677236854063
Finished migration UpdateRunningExecutionStatus1677236854063
Starting migration CreateVariables1677501636754
Finished migration CreateVariables1677501636754
Starting migration CreateExecutionMetadataTable1679416281778
Finished migration CreateExecutionMetadataTable1679416281778
Starting migration AddUserActivatedProperty1681134145996
Finished migration AddUserActivatedProperty1681134145996
Starting migration RemoveSkipOwnerSetup1681134145997
Finished migration RemoveSkipOwnerSetup1681134145997
Starting migration MigrateIntegerKeysToString1690000000000
Finished migration MigrateIntegerKeysToString1690000000000
Starting migration SeparateExecutionData1690000000020
Finished migration SeparateExecutionData1690000000020
Starting migration RemoveResetPasswordColumns1690000000030
Finished migration RemoveResetPasswordColumns1690000000030
Starting migration AddMfaColumns1690000000030
Finished migration AddMfaColumns1690000000030
Starting migration AddMissingPrimaryKeyOnExecutionData1690787606731
Finished migration AddMissingPrimaryKeyOnExecutionData1690787606731
Starting migration CreateWorkflowNameIndex1691088862123
Finished migration CreateWorkflowNameIndex1691088862123
Starting migration CreateWorkflowHistoryTable1692967111175
Finished migration CreateWorkflowHistoryTable1692967111175
Starting migration ExecutionSoftDelete1693491613982
Finished migration ExecutionSoftDelete1693491613982
Starting migration DisallowOrphanExecutions1693554410387
Finished migration DisallowOrphanExecutions1693554410387
Starting migration MigrateToTimestampTz1694091729095
Finished migration MigrateToTimestampTz1694091729095
Starting migration AddWorkflowMetadata1695128658538
Finished migration AddWorkflowMetadata1695128658538
Starting migration ModifyWorkflowHistoryNodesAndConnections1695829275184
Finished migration ModifyWorkflowHistoryNodesAndConnections1695829275184
Starting migration AddGlobalAdminRole1700571993961
Finished migration AddGlobalAdminRole1700571993961
Starting migration DropRoleMapping1705429061930
Finished migration DropRoleMapping1705429061930
Starting migration RemoveFailedExecutionStatus1711018413374
Finished migration RemoveFailedExecutionStatus1711018413374
Starting migration MoveSshKeysToDatabase1711390882123
[MoveSshKeysToDatabase1711390882123] No SSH keys in filesystem, skipping
Finished migration MoveSshKeysToDatabase1711390882123
Starting migration RemoveNodesAccess1712044305787
Finished migration RemoveNodesAccess1712044305787
Starting migration CreateProject1714133768519
Finished migration CreateProject1714133768519
Starting migration MakeExecutionStatusNonNullable1714133768521
Finished migration MakeExecutionStatusNonNullable1714133768521
Starting migration AddActivatedAtUserSetting1717498465931
Finished migration AddActivatedAtUserSetting1717498465931
Starting migration AddConstraintToExecutionMetadata1720101653148
Finished migration AddConstraintToExecutionMetadata1720101653148
Starting migration FixExecutionMetadataSequence1721377157740
Finished migration FixExecutionMetadataSequence1721377157740
Starting migration CreateInvalidAuthTokenTable1723627610222
Finished migration CreateInvalidAuthTokenTable1723627610222
Starting migration RefactorExecutionIndices1723796243146
Finished migration RefactorExecutionIndices1723796243146
Starting migration CreateAnnotationTables1724753530828
Finished migration CreateAnnotationTables1724753530828
Starting migration AddApiKeysTable1724951148974
Finished migration AddApiKeysTable1724951148974
Starting migration CreateProcessedDataTable1726606152711
Finished migration CreateProcessedDataTable1726606152711
Starting migration SeparateExecutionCreationFromStart1727427440136
Finished migration SeparateExecutionCreationFromStart1727427440136
Starting migration AddMissingPrimaryKeyOnAnnotationTagMapping1728659839644
Finished migration AddMissingPrimaryKeyOnAnnotationTagMapping1728659839644
Starting migration UpdateProcessedDataValueColumnToText1729607673464
Finished migration UpdateProcessedDataValueColumnToText1729607673464
Starting migration AddProjectIcons1729607673469
Finished migration AddProjectIcons1729607673469
Starting migration CreateTestDefinitionTable1730386903556
Finished migration CreateTestDefinitionTable1730386903556
Starting migration AddDescriptionToTestDefinition1731404028106
Finished migration AddDescriptionToTestDefinition1731404028106
Starting migration MigrateTestDefinitionKeyToString1731582748663
Finished migration MigrateTestDefinitionKeyToString1731582748663
Starting migration CreateTestMetricTable1732271325258
Finished migration CreateTestMetricTable1732271325258
Starting migration CreateTestRun1732549866705
Finished migration CreateTestRun1732549866705
Starting migration AddMockedNodesColumnToTestDefinition1733133775640
Finished migration AddMockedNodesColumnToTestDefinition1733133775640
Starting migration AddManagedColumnToCredentialsTable1734479635324
Finished migration AddManagedColumnToCredentialsTable1734479635324
Starting migration AddStatsColumnsToTestRun1736172058779
Finished migration AddStatsColumnsToTestRun1736172058779
Starting migration CreateTestCaseExecutionTable1736947513045
Finished migration CreateTestCaseExecutionTable1736947513045
Version: 1.78.1

Editor is now accessible via:
http://localhost:5678/

Press "o" to open in Browser.
