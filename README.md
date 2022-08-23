# docker-templates
docker compose templates for my various applications

For other repos and images checkout

https://github.com/novaspirit/pi-hosted/tree/master/images

https://github.com/ibracorp/templates

```
curl -sSL https://get.docker.com | sh || error "Failed to install Docker."
sudo usermod -aG docker $USER || error "Failed to add user to the Docker usergroup."
echo "Remember to logoff/reboot for the changes to take effect."

```


```
docker network create proxy
docker network create secure
```

Clone this repo, copy the `sample.env` to `.env` and link it to every folder
``` 
ln /path/to/global/.env /path/to/app_folder/.env 
```