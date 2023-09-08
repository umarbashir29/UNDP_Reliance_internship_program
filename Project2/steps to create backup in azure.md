#steps to create a backup account
1. login into azure portal
2. goto resources to create a storage account
3. after creating the storage account goto container
4. create new container
5. generate SAS key
6. goto access key and shared access tokens to configure the permission on what acttion to perform on the container.
and generate tokens and select the validity of the access, then generate SAS Token which contain the URL, that will grant you read and write
7. CREATE credentials
8. then use the querry to create backup using the url generate.
