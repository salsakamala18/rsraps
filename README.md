
| Status | Response  |
| ------ | --------- |
| 200    |Some code here:<br><pre lang="json">{&#13;  "id": 10,&#13;  "username": "alanpartridge"&#13;}</pre>|
| 400    |Some text here|


## Contents
- [Python](#python)
- [PyGithub](#pygithub)
- [Project](#project)

## Python

[GITHUB_API_URL](https://devopslearning.medium.com/day-13-101-days-of-devops-github-api-using-python-and-pygithub-module-c1bcbaaeada7)
```bash
GITHUB_API_URL = "https://api.github.com/"
```
[tag_prefix](https://github.com/BLAKE3-team/BLAKE3/blob/fc2f7e4206f016b0cac0593f23a7d5976ce066e6/.github/workflows/upload_github_release_asset.py#L12)
```bash
tag_prefix = "refs/tags/"
```

[owner](https://martinheinz.dev/blog/25)
```bash
owner = "MartinHeinz"
```

[repo](https://martinheinz.dev/blog/25)
```bash
repo = "python-project-blueprint"
```

[logging]()
```bash
logging.basicConfig(level=logging.DEBUG,)
```
## PyGithub
[github]()
```bash
access_github = github.Login(login=f"{user_name}", password=f"{user_password}")
```

KO-KO
[github python API (PyGithub)](https://www.yocto.co.kr/m/102)

## Project
[Discover swinton/pygithub-playground Open Source project](https://opensource-heroes.com/r/swinton/pygithub-playground)
