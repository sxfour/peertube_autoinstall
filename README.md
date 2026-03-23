1. SSH into the machine and assume root privileges.
2. Create and navigate to a directory: `mkdir auto_script && cd auto_script`.
    You can also use own directory.
3. Run the following command to start the script.
    ```bash
    curl -lO https://code.honeytreetech.com/fediverse/peertube/auto-installer/auto_script.sh && sudo chmod +x auto_script.sh && ./auto_script.sh
    ```
4. Input the requested details as per the following table.
    | Name | Description | Mandatory | Optional | Default Value | 
    |------|---------|-----------|----------|---------------|
    | `admin_email`|Admin Email| &checkmark; | &#10006;| &#10006; | 
    |`domain_name` | Domain name| &checkmark;| &#10006;| &#10006;|
    |`smtp_host` | SMTP host | &checkmark;|  &#10006;| &#10006; | 
    |`smtp_port` | SMTP port| &checkmark;| &#10006;| &#10006;|
    |`smtp_user` | SMTP user| &checkmark;| &#10006;| &#10006;|
    |`smtp_password` | SMTP password| &checkmark;| &#10006;| &#10006;|
    |`smtp_from` | SMTP from| &checkmark;| &#10006;| &#10006;|
    |`db_user` | Database user| &#10006;| &checkmark;|peertube |
    |`db_password` | Database Password| &#10006;| &checkmark;|pass_XXXXXXXXX (whereX is Random character) |
    |`db_name` | Database name| &#10006;| &checkmark;|peer_XXXXXXXXX (whereX is Random character) |
    |`port` | SSH port | &checkmark;| &#10006;| &#10006;|

                                
5. Accept terms of service as prompted.
6. Follow further on-screen instructions to complete the setup.
