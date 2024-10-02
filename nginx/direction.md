1. put `gunicorn.service` at `etc/systemd/system/` directory
2. Run `enable_gunicorn.sh` script

3. Rename and put `myapp` at `etc/nginx/sites-available/` directory
4. Run `enable_nginx.sh` script

## OPTIOAL
- Run `enable_ssl.sh`, and `firewall.sh` scripts.

## Finally

- Rename and Put `nginx.yaml` in `.github/workflows/` directory

## Important

Dont Forget to add `AWS_HOST`, `AWS_USER`, and `AWS_SSH_KEY` in your github repository secrets.