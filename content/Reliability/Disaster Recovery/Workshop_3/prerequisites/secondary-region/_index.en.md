+++
title = "Secondary Region"
date =  2021-05-11T11:43:28-04:00
weight = 5
+++

1.1 Create the application in the Secondary region (us-west-1) by launching this  [CloudFormation Template](https://console.aws.amazon.com/cloudformation/home?region=us-west-1#/stacks/create/template?stackName=Warm-Secondary&templateURL=https://ee-assets-prod-us-east-1.s3.amazonaws.com/modules/630039b9022d4b46bb6cbad2e3899733/v1/WarmStandbyDR.yaml).

1.2  Specify stack details.

Change the **IsPrimary** parameter to value `no`.

{{% notice info %}}
**Leave IsPromote and LatestAmiId as the default values**
{{% /notice %}}

1.3 Click **Next** to continue.

{{< img sr-4.png >}}

1.4 Leave the **Configure stack options** page defaults and click **Next** to continue.

1.5 Scroll to the bottom of the page and click the **checkbox** to acknowledge IAM role creation, then click **Create stack**.

{{< img sr-5.png >}}

{{% notice info %}}
**Wait for the stack creation to complete**.
{{% /notice %}}

{{< img sr-5.png >}}
