The _locals.tf_ file is the only variables you will need to pass in.

For IAM Permissions you need to move the file back to the root of the directory and then apply the _add_developer_iam.tf_ The file is inside the iam permissions folder and after* you have applied the permissions in the k8s cluster first then you can add the users with permissions. Remember to move the _add_developer_iam.tf_ file back to the root of the directory.
