# Granting Access to Guest Users in Azure Storage Account
## Purpose
The purpose of this repository is to help organizations effectively manage external user access to their Azure Storage accounts, ensuring secure and efficient collaboration with guest users.


## Step 1: Invite Guest Users

1. **Navigate to Microsoft Entra ID (Azure Active Directory)**:
   - Go to the Azure Portal and sign in.
   - Select **Azure Active Directory** from the left-hand menu.

2. **Invite External User**:
   - Click on **Users** > **Invite external user**.
   - Choose **Invite user**.
   - Enter the guest user's email address (e.g., Gmail, Yahoo).
   - Optionally, add a personal message.
   - Click **Invite** to send the invitation.

## Step 2: Assign Roles to Guest Users

1. **Access Control (IAM)**:
   - Navigate to the Storage account you want to grant access to.
   - Select **Access Control (IAM)** from the left-hand menu.

2. **Add Role Assignment**:
   - Click on **+ Add** > **Add role assignment**.
   - Choose a role that defines the permissions you want to grant (e.g., Storage Blob Data Contributor, Storage Blob Data Reader).
   - Under **Assign access to**, select **User, group, or service principal**.
   - Search for and select the guest user you invited.
   - Click **Review + assign** to complete the process.

## Step 3: Guest User Accepts Invitation

1. **Accept Invitation**:
   - The guest user will receive an email invitation.
   - They need to click on the link in the email to accept the invitation and join your directory.

## Step 4: Verify Access

1. **Verify Access**:
   - Ensure the guest user can access the Storage account by having them log in to the Azure Portal.
   - They should be able to access the data based on the role assigned.
