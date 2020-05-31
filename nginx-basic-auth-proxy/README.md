```bash
% docker run --rm nginx:latest echo "ユーザー名:$(openssl passwd -apr1 パスワード)" >> htpasswd
```
