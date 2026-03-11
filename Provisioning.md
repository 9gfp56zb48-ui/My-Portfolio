For this lab, with the use of powershell I automated the provisioning of Users and Groups. I implemented a tiered Organizational Unit (OU) structure to facilitate Administrative Partitioning. By separating Admin_Accounts and Service_Accounts from standard Users, we can apply more restrictive Group Policy Objects (GPOs), such as enforcing MFA or restricting login hours, which are core tenets of Privileged Access Management (PAM).

![Group Provisioning](https://github.com/9gfp56zb48-ui/My-Portfolio/blob/7836bd1d0322aaeacac5573b55f334fc20afb044/images/GroupsProvisioning.png)

![User Provisioning](https://github.com/9gfp56zb48-ui/My-Portfolio/blob/7836bd1d0322aaeacac5573b55f334fc20afb044/images/PSUserProvsioning.png)

