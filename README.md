# azure-ubuntu-apache-lab
Ubuntu Apache web server lab on Azure — step-by-step

Ways to create resources on azure
1 Azure Portal
2 Azure powershell
    Login-AzAccount -TenantId 1e02b008-fc67-41f9-af7d-e8fe95cecaab -SubscriptionId 55d9e7d6-21d8-4303-aa36-0385f27b115e
    Connect-AzAccount
    Disconnect-AzAccount

    New-AzResourceGroup -Name powershell -Location uksouth
    Get-AzResourceGroup
    Remove -AzureResourceGroup -Name powershell
