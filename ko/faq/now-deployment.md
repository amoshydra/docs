---
title: Now를 사용한 배포
description: Now를 사용하여 배포하려면?
---

# Now를 사용하여 배포하려면?

[now.sh](https://zeit.co/now) 을 사용하여 배포하려면 `package.json` 을 다음처럼 작성하는 것을 추천합니다:

```json
{
  "name": "my-app",
  "dependencies": {
    "nuxt": "latest"
  },
  "scripts": {
    "dev": "nuxt",
    "build": "nuxt build",
    "start": "nuxt start"
  }
}
```

이걸로 `now` 를 사용할 수 있어요！！

메모: `.nuxt`를 `.npmignore` 혹은 `.gitignore`에 등록해두는 것을 추천합니다.
