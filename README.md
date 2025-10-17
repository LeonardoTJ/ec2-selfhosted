# ec2-selfhosted
Testing self hosted service install with docker compose

## Directory Structure
```
/home/ubuntu/selfhosted/
├── docker-compose.yml
├── nginx/
│   ├── conf.d/
│   │   ├── example.com.conf
│   │   └── redlib.example.com.conf
│   └── html/
│       └── index.html
└── cloudflare/
    └── origin-cert.pem
    └── origin-key.pem
```