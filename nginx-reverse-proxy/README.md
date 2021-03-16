## ## nginx-reverse-proxy

In this example we have a reverse proxy for two server environments. We reset proxied headers to origin request headers and filter the pre environment IPs. The proxy redirects are using an upstream in order to load balance servers in a simple way.
