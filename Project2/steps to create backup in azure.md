#steps to create a backup account 
1. login into azure portal ![login to azure](https://github.com/umarbashir29/UNDP_Reliance_internship_program/assets/139869693/26dea49f-ab07-4b40-8ffc-bd8f63bc4e3a)
2. goto resources to create a storage account ![creating storage account](https://github.com/umarbashir29/UNDP_Reliance_internship_program/assets/139869693/3b524884-01fa-4849-8504-52d34eb68db3)

3. after creating the storage account goto container 
4. create new container ![creating container](https://github.com/umarbashir29/UNDP_Reliance_internship_program/assets/139869693/78108b63-34e6-4db6-bc64-38a3f7d91dde)

5. generate SAS key ![generating sas token](https://github.com/umarbashir29/UNDP_Reliance_internship_program/assets/139869693/db725f59-1ec1-4305-8a82-75bfd437eb89)

6. goto access key and shared access tokens to configure the permission on what acttion to perform on the container, and generate tokens and select the validity of the access, then generate SAS Token which contain the URL, that will grant you read and write ![grant access using shared access](https://github.com/umarbashir29/UNDP_Reliance_internship_program/assets/139869693/eae3ec1f-91e6-4339-b88b-2df8c92a87b5)

7. CREATE credentials 
8. then use the querry to create backup using the url generate. ![backup database](https://github.com/umarbashir29/UNDP_Reliance_internship_program/assets/139869693/b39251a8-3a80-4384-b9ec-f31b9281fea6)
9. go to azure container to confirm the backup ![confirming Database in azure](https://github.com/umarbashir29/UNDP_Reliance_internship_program/assets/139869693/697538cf-832c-4000-b762-a0008495a026)
10. to try restoring the database you have to delete it, but make sure the Backup was successfully
11. after successfully restoring a deleted database  ![after successfully restoring a db](https://github.com/umarbashir29/UNDP_Reliance_internship_program/assets/139869693/7bf63b01-7865-46c1-94ad-da4414d0b8f3)

