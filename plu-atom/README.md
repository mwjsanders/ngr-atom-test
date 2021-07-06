# Generate ATOM files

```cmd
docker run -it -v `pwd`/config:/config -v `pwd`/output:/output --name atom pdok/atom-generator ./atom -f=/config/values.yaml -o=/output
```
