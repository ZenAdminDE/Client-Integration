# Create Service Account for Google Workspace Migration Products


This script is designed to automate the steps needed to create a service account for  ZenAdmin & Google Workspace Integration. It's  meant to be executed within a Google Cloud Shell. The script generates a service account's private key JSON file which are meant to be shared with the ZenAdmin  Spoc. The scripts automate the following:

*   Creates a GCP project
*   Enables APIs
*   Creates a service account
*   Authorizes the service account
*   Creates and downloads a service account key


## Usage


To create an authorized service account for Google Workspace Migration for
Microsoft Exchange, copy and paste the command below in Cloud Shell.

1.  [Open Cloud Shell](https://ssh.cloud.google.com/cloudshell/editor?shellonly=true)
2.  Copy and paste the following command into Cloud Shell and press Enter.

```
python3 <(curl -s -S -L https://git.io/gwmme-create-service-account)
```

### Credits

These scripts was forked from (https://support.google.com/a/answer/6291304?hl=en#zippy=%2Coption-use-an-automated-script-to-create-the-account).


