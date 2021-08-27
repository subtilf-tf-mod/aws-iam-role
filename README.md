# Terraform module of  AWS - IAM Policy - Just for learn purpose!!! 

ll terraform modules from my repositories is only for learn purpose, so it can be broken, incomplete or not working well!

So if you use that code be careful and you will be at your own!!! Good lucky!!!

# What is an IAM Policy?
An IAM role is an IAM identity that you can create in your account that has specific permissions. An IAM role is similar to an IAM user, in that it is an AWS identity with permission policies that determine what the identity can and cannot do in AWS. However, instead of being uniquely associated with one person, a role is intended to be assumable by anyone who needs it. Also, a role does not have standard long-term credentials such as a password or access keys associated with it. Instead, when you assume a role, it provides you with temporary security credentials for your role session.

You can use roles to delegate access to users, applications, or services that don't normally have access to your AWS resources. For example, you might want to grant users in your AWS account access to resources they don't usually have, or grant users in one AWS account access to resources in another account. Or you might want to allow a mobile app to use AWS resources, but not want to embed AWS keys within the app (where they can be difficult to rotate and where users can potentially extract them). Sometimes you want to give AWS access to users who already have identities defined outside of AWS, such as in your corporate directory. Or, you might want to grant access to your account to third parties so that they can perform an audit on your resources.

Source of information and image: https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html

# Motivation
I wrote a lot of codes using terraform modules and for each individual project I had to replicated the modules.

Therefore as terraform accept to work with remote repositories I decided to use github as my source of terraform modules.

# About the project
This project just store the common git files (license and readme.md) and terraform files (main, var and output).