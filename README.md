# Ex: 10 - IAM-working-overview
### NAME: Rhudhra phriyamvadha K S
### REG NO: 212224040275
## Aim
To explore and configure AWS Identity and Access Management (IAM) users, groups, and policies, and to verify permissions for accessing Amazon S3 and Amazon EC2 resources.
## Procedure
1. Start the AWS Lab and open the **AWS Management Console**.
2. Open **IAM → Users** and verify `user-1`, `user-2`, and `user-3`.
3. Open **User groups** and verify the groups **S3-Support, EC2-Support, and EC2-Admin** and their attached policies.
4. Add:

   * `user-1` → **S3-Support**
   * `user-2` → **EC2-Support**
   * `user-3` → **EC2-Admin**
5. Open the IAM **Sign-in URL** and sign in as each user using the given lab credentials.
6. Test `user-1`: verify **S3 access** and confirm **EC2 access is denied**.
7. Test `user-2`: verify **EC2 read-only access** and confirm that stopping an EC2 instance is denied; verify **S3 access is denied**.
8. Test `user-3`: open **EC2**, select `LabHost`, and **stop the instance** successfully.
9. Submit the lab and check the **Grades/Submission Report**.
10. End the lab after completing all tasks.
## Output
<img width="1920" height="1200" alt="Screenshot (159)" src="https://github.com/user-attachments/assets/f09651ee-47c9-4628-a2df-e43f5e443453" />
<img width="1920" height="1200" alt="Screenshot (160)" src="https://github.com/user-attachments/assets/1a580c97-a155-4b70-924a-5bfd9d595fd5" />
<img width="1920" height="1200" alt="Screenshot (161)" src="https://github.com/user-attachments/assets/6bb18d1a-5e8c-4480-b7a8-88b59fc24e70" />
<img width="1920" height="1200" alt="Screenshot (162)" src="https://github.com/user-attachments/assets/0ed1c357-eccc-4236-8419-aab66fef3db6" />
<img width="1920" height="1200" alt="Screenshot (163)" src="https://github.com/user-attachments/assets/bdba6b2f-2262-401d-a309-c252c3df4635" />
<img width="1920" height="1200" alt="Screenshot (164)" src="https://github.com/user-attachments/assets/a20b361e-0401-4ed9-888a-34477adbf6e3" />

## Result
The IAM users were successfully assigned to their respective groups, and the required permissions were verified. `user-1` received S3 read-only access, `user-2` received EC2 read-only access, and `user-3` received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.
