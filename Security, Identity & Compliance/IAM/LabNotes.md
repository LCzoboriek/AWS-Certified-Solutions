## IAM

- Root User:

- Always use MFA for the root user of your AWS account as they can do absolutely anything on AWS with it. You should really be creating users and utilisng them.

IAM always is operable in the Global scale.

Create group then assign certain access policies to that group.

There are job functions already defined, which will give the generic access reqs for that job role.

You can look at the json data and see what access that role/group has

New Users have no permissions at first

New users are assigned access key and secret access keys when first created. You can however stop that from happening by default.
