# Goanywhere

- Build

```sh
make build
```

- Run

```sh
./bin/goanywhere
```

- Forward the api

```sh
curl http://127.0.0.1:8080/forward?url=${url}

curl http://127.0.0.1:8080/forward?url=https%3A%2F%2Fapi.coingecko.com%2Fapi%2Fv3%2Fsimple%2Fprice%3Fids%3Dbitcoin%2Cethereum%26vs_currencies%3Dusd
```