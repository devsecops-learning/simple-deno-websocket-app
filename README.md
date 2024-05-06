### Pre requistes

> Install DENO
```sh
curl -fsSL https://deno.land/install.sh | sh
export DENO_INSTALL="/root/.deno"
export PATH="$DENO_INSTALL/bin:$PATH"
```

> Firewall Ports Allowed(80) // AWS - Security Group
```
Port 3000
```

### Check
```sh
deno --version
```

### Run
```sh
git clone https://github.com/devsecops-learning/simple-deno-websocket-app

cd simple-deno-websocket-app

deno run --allow-read --allow-net server.js
```
