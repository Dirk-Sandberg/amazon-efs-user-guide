# BackupPolicy<a name="API_BackupPolicy"></a>

The backup policy for the file system used to create automatic daily backups\. If status has a value of `ENABLED`, the file system is being automatically backed up\. For more information, see [Automatic backups](https://docs.aws.amazon.com/efs/latest/ug/awsbackup.html#automatic-backups)\.

## Contents<a name="API_BackupPolicy_Contents"></a>

 ** Status **   <a name="efs-Type-BackupPolicy-Status"></a>
Describes the status of the file system's backup policy\.  
+  ** `ENABLED` ** \- EFS is automatically backing up the file system\.
+  ** `ENABLING` ** \- EFS is turning on automatic backups for the file system\.
+  ** `DISABLED` ** \- Automatic back ups are turned off for the file system\.
+  ** `DISABLING` ** \- EFS is turning off automatic backups for the file system\.
Type: String  
Valid Values:` ENABLED | ENABLING | DISABLED | DISABLING`   
Required: Yes

## See Also<a name="API_BackupPolicy_SeeAlso"></a>

For more information about using this API in one of the language\-specific AWS SDKs, see the following:
+  [AWS SDK for C\+\+](https://docs.aws.amazon.com/goto/SdkForCpp/elasticfilesystem-2015-02-01/BackupPolicy) 
+  [AWS SDK for Go](https://docs.aws.amazon.com/goto/SdkForGoV1/elasticfilesystem-2015-02-01/BackupPolicy) 
+  [AWS SDK for Java V2](https://docs.aws.amazon.com/goto/SdkForJavaV2/elasticfilesystem-2015-02-01/BackupPolicy) 
+  [AWS SDK for Ruby V3](https://docs.aws.amazon.com/goto/SdkForRubyV3/elasticfilesystem-2015-02-01/BackupPolicy) 