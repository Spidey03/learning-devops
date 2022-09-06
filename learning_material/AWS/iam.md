## IAM


### IAM User
<!--- #user --->
&nbsp;&nbsp;&nbsp;&nbsp;The IAM user represents the person or service who uses the IAM user to interact with AWS. A primary use for IAM users is to give people the ability to sign in to the AWS Management Console for interactive tasks and to make programmatic requests to AWS services using the API or CLI.
<!--- #user --->

<!--- #user-properties --->
&nbsp;&nbsp;&nbsp;&nbsp; The IAM user consist of a name, password & upto two access keys. And while creating IAM user, user can be grant permissions either by adding as a member of user group or directly assigning roles/permissions.
<!--- #user-properties --->

### Groups

<!--- #group --->
#### IAM User Groups
&nbsp;&nbsp;&nbsp;&nbsp;An IAM user group is a collection of IAM users. User groups lets you specify permissions for multiple users, which can make it easier to manage the permissions for those users.
<!--- #group --->

<!--- #group-characteristics --->
#### Group Characteristics
- A group can contain many users, and a user can belong to multiple user groups.
- User groups can't be nested.
- Number of groups & Size of each group is limited.
<!--- #group-characteristics --->