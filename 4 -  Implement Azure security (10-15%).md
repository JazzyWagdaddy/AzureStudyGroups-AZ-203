# Implement Azure security (10-15%)

You may want to consider taking the [Microsoft Implementing Authentication and Secure Data](https://cloudsociety.fastlane.live/courses/course-v1:Microsoft+AZ-300.5+2018_T3/info) course.

## Implement authentication 
* Implement authentication by using certificates, forms-based authentication, or tokens
    * [What is authentication?](https://docs.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios)
    * [What are authentication methods?](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-authentication-methods)
* Implement multi-factor or Windows authentication by using Azure AD 
    * [Deploy cloud-based Azure Multi-Factor Authentication](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-getstarted)
    * [Configure Azure Multi-Factor Authentication settings](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-mfasettings)
* Implement OAuth2 authentication
    * [Authorize access to Azure Active Directory web applications using the OAuth 2.0 code grant flow](https://docs.microsoft.com/en-us/azure/active-directory/develop/v1-protocols-oauth-code)
* Implement Managed Service Identity (MSI)/Service Principal authentication 
    * [What is managed identities for Azure resources?](https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/overview)
    * [Use a Windows VM system-assigned managed identity to access Resource Manager](https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/tutorial-windows-vm-access-arm)
    * [Use a Linux VM system-assigned managed identity to access Azure Resource Manager](https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/tutorial-linux-vm-access-arm)

## Implement access control 
* Implement CBAC (Claims-Based Access Control) authorization
    * [Claims-based Authorization](https://docs.microsoft.com/en-us/dotnet/framework/security/claims-based-authorization-using-wif#claims-based-authorization)
    * [A Guide to Claims-Based Identity and Access Control, Second Edition - Book Download](https://www.microsoft.com/en-us/download/details.aspx?id=28362)
    * [Azure Identity Management and access control security best practices](https://docs.microsoft.com/en-us/azure/security/azure-security-identity-management-best-practices)
* Implement RBAC (Role-Based Access Control) authorization
    * [Understand role definitions for Azure resources](https://docs.microsoft.com/en-us/azure/role-based-access-control/role-definitions)
    * [What is role-based access control (RBAC) for Azure resources?](https://docs.microsoft.com/en-us/azure/role-based-access-control/overview)
    * [Tutorial: Grant a user access to Azure resources using RBAC and the Azure portal](https://docs.microsoft.com/en-us/azure/role-based-access-control/quickstart-assign-role-user-portal)
    * [Tutorial: Grant a user access to Azure resources using RBAC and Azure PowerShell](https://docs.microsoft.com/en-us/azure/role-based-access-control/tutorial-role-assignments-user-powershell)
    * [Tutorial: Create a custom role for Azure resources using Azure CLI](https://docs.microsoft.com/en-us/azure/role-based-access-control/tutorial-custom-role-cli)
    * Complete all five tutorials
* Create shared access signatures
    * [Using shared access signatures (SAS)](https://docs.microsoft.com/en-us/azure/storage/common/storage-dotnet-shared-access-signature-part-1)
    * [Shared Access Signatures, Part 2: Create and use a SAS with Blob storage](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-dotnet-shared-access-signature-part-2)
    * [Getting Started with Shared Access Signatures (SAS)](https://azure.microsoft.com/en-us/resources/samples/storage-dotnet-sas-getting-started/)

## Implement secure data solutions 
* Encrypt and decrypt data at rest and in transit
    * [Define data protection strategy for your hybrid identity solution](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/plan-hybrid-identity-design-considerations-data-protection-strategy)
* Create, read, update, and delete keys, secrets, and certificates by using the KeyVault API
    * [What is Azure Key Vault?](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-overview)
    * [Azure Key Vault Developer's Guide](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-developers-guide)


