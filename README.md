# Ex: 10 - IAM-working-overview
### NAME: THEJA SREE G
### REG NO: 212224110056
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
<img width="1682" height="869" alt="image" src="https://github.com/user-attachments/assets/56d2ce19-6b57-4e9b-a1ba-70159d0e56f0" />

<img width="1686" height="860" alt="image" src="https://github.com/user-attachments/assets/d79a96b3-e753-4471-b403-bccd627c6237" />

<img width="1685" height="855" alt="image" src="https://github.com/user-attachments/assets/d9f4d103-a164-4162-bf72-099edc259446" />

<img width="1583" height="848" alt="image" src="https://github.com/user-attachments/assets/45e3b8db-889a-49a5-a5fc-bf04e51613ac" />

<img width="1583" height="807" alt="image" src="https://github.com/user-attachments/assets/91145241-a581-4f1d-b850-bd33d0a73c9c" />

<img width="1920" height="1200" alt="Screenshot (164)" src="https://github.com/user-attachments/assets/a20b361e-0401-4ed9-888a-34477adbf6e3" />

## Result
The IAM users were successfully assigned to their respective groups, and the required permissions were verified. `user-1` received S3 read-only access, `user-2` received EC2 read-only access, and `user-3` received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.
