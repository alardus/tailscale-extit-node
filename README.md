# tailscale-extit-node

```curl -fsSL https://tailscale.com/install.sh | sh```

```echo 'net.ipv4.ip_forward = 1' | sudo tee -a /etc/sysctl.d/99-tailscale.conf```

```echo 'net.ipv6.conf.all.forwarding = 1' | sudo tee -a /etc/sysctl.d/99-tailscale.conf```

```sudo sysctl -p /etc/sysctl.d/99-tailscale.conf```



```sudo tailscale up --advertise-exit-node```
