# skyOS Ansible Playbooks
Ansible playbooks for deploying and updating skyOS

## Playbooks
`update.yml` - Pull the latest image from the GitHub docker registry and restart services

## Variables

 * `github_key` - Personal access token for Docker container registry

    ```
    <username>: <token>
    ```

 * `skyOS_dir` - Path to `docker-compose.yml` 
