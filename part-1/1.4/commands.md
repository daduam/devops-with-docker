```console
> docker run -it --name=curler ubuntu sh -c 'apt update && apt upgrade; apt install -y curl; echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;'
```
