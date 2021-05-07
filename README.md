#Compiled on 01/05/2021


These APIs can help you to provide all the details in one go and perform the validation on resource groups without doing any sort of copy-paste. In our earlier approach, we had to fetch the list of resources from Powershell and then paste the well-structured resource list into Postman POST API to fetch the validation results. But in this case, all you need to do is fill in the environmental variables and that's it. For every other resource group, you just need to replace the RG name in the variables. The order in which these APIs need to be run is - 

1. Get Azure AD token
2. Fetch Resources in Resource group
3. Resources to Validate
4. Get Validation Results
