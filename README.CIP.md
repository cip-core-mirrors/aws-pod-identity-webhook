# CIP Amazon EKS Pod Identity Webhook

[Version: v0.2.1]


## What is it?
See [README.md](./README.md) for detailed information about this component based on Amazon EKS Pod Identity Webhook.



## Why creating a custom version?

This component greatly simplify operations app-specific AWS IAM users management and related
Access Key / Secret Key (AKSK).

Cloud Innovation Platform extensively OpenShift on AWS from the beginning of the project
but as we are progressively integrating CSP's managed kubernetes services such as AWS EKS,
Azure AKS and our internal Cloud Platform, we need to build our own version of this operator.

We'll try to contribute contribute as much as possible to the upstream repository and reserve
this repo to our platforms-specific configuration & features.



## License

This component is licensed under Apache License 2.0, same as the upstream component.

