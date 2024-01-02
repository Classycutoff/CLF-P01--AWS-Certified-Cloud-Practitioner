# Multi-factor Authentication (MFA)

[AWS multi-factor authentication](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#enable-mfa-for-privileged-users) (MFA) is an AWS Identity and Access Management ([[AWS IAM]]) [LINK](https://aws.amazon.com/iam/) best practice that requires a second authentication factor in addition to user name and password sign-in credentials. You can enable MFA at the AWS account level and for root and IAM users you have created in your account.  

_AWS is expanding eligibility for its free MFA security key program. Verify your eligibility and order your [**free MFA key**](https://aws.amazon.com/security/amazon-security-initiatives/free-mfa-security-key/)._

With MFA enabled, when a user signs in to the [AWS Management Console](https://console.aws.amazon.com/console/home), they are prompted for their user name and password— _something they know_—and an authentication code from their MFA device— _something they have_ (or if they use a biometrics-enabled authenticator, _something they are_). Taken together, these factors improve security for your AWS accounts and resources.  

We recommend that you require your human users to use temporary credentials when accessing AWS. Your users can use an identity provider to federate into AWS, where they can authenticate with their corporate credentials and MFA configurations. To manage access to AWS and business applications, we recommend that you use [AWS IAM Identity Center](https://aws.amazon.com/iam/identity-center/). For more information, see the [IAM Identity Center User Guide](https://docs.aws.amazon.com/singlesignon/latest/userguide/what-is.html).

See the following available MFA options that you can use with your IAM MFA implementation. You can download virtual authenticator apps through the links provided, or you can acquire a hardware MFA device from the respective manufacturer. After you've acquired a supported virtual or hardware MFA device, AWS does not charge additional fees for using MFA.
