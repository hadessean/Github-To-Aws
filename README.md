Step 1: Create an OIDC provider in your account

The first step in this process is to create an OIDC provider which you will use in the trust policy for the IAM role used in this action.
1. Adding the identity provider to AWS

Open AWS Console -> Identity and Access Management (IAM) -> Identity providers -> Add Provider

References: AWS documentation & configure-aws-credentials

    Audience:sts.amazonaws.com
    Provider URL: https://token.actions.githubusercontent.com
