# hexo-deployer-upyun
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FMenci%2Fhexo-deployer-upyun.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FMenci%2Fhexo-deployer-upyun?ref=badge_shield)

UPYUN deployer for Hexo.

```
npm install hexo-deployer-upyun --save
```

# Usage
Example configure:

```yaml
deploy:
  type: upyun
  bucket: bucket
  operator: operator
  password: password
  endpoint: v0.api.upyun.com
  secret: secret
  try_times: 5
  ignore_path_re:
    dir: null
    file: ".DS_Store$"
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FMenci%2Fhexo-deployer-upyun.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FMenci%2Fhexo-deployer-upyun?ref=badge_large)