```bash
% docker run --rm nginx:latest echo "ユーザー名:$(openssl passwd -apr1 パスワード)" >> htpasswd
```

```bash
% docker-compose up -d
```

```bash
% docker-compose logs -ft
```

```bash
% curl -v http://localhost
```
