1. Req: Ubuntu 20.04 / SSH into the machine and assume root privileges.
2. Clone and navigate to a directory:
   ```bash
    git clone https://github.com/sxfour/peertube_autoinstall && cd peertube_autoinstall
    ```
4. Run the following command to start the script.
    ```bash
    sudo chmod +x auto_script.sh && ./auto_script.sh
    ```
5. Input the requested details as per the following table.
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

                                
6. Accept terms of service as prompted.
7. Follow further on-screen instructions to complete the setup.
<img width="1864" height="839" alt="image" src="https://github.com/user-attachments/assets/01b8d93b-dbae-4ee4-98fe-058918a67ebd" />
