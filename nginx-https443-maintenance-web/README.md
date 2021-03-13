## https443-maintenance-web

Run it to create a ngix webserver on port 443 to return an html maintenance webpage while deploying or maintaning your main webserver.

Build and run it:
```
1.- sudo docker build -t https443-maintenance-web .
2.- docker run -p 80:80 -p 443:443 -it --rm -v $PWD/ssl:/etc/nginx/ssl/ https443-maintenance-web
```

---

If self digned probably run:
```
sudo openssl dhparam -out ./dhparam.pem 4096
```