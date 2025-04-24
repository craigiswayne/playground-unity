### Testing Locally
Build Web Version

```shell
docker build -t local-unity-web-test .
docker run -p 8384:443 local-unity-web-test
```

open https://localhost:8384/ in your browser