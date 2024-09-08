<br>

## Notes

### Creating Secrets

The script [secrets.sh.template](secrets.sh.template) outlines the creation of Amazon Secrets.  The underlying `json` file may consist of one or more secrets; study [settings.json.template](settings.json.template).

```shell
bash .iac/secrets/secrets.sh
```

If successful, the terminal output pattern is akin to

```json
{
    "ARN": "arn:aws:secretsmanager:{region.code}:{account.identifier}:secret:{name}...",
    "Name": "{name}",
    "VersionId": "..."
}
```

<br>
<br>

<br>
<br>

<br>
<br>

<br>
<br>
