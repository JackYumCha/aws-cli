# aws-cli

## aws-use
when you do not need MFA and just need to the credentials: AWS_DEFAULT_REGION, AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY

```cmd
aws-use [profile-name (optional)]
```
## aws-mfa
when you also need to use MFA to obtain AWS_SESSION_TOKEN
```cmd
aws-mfa [profile-name (optional)]
```
