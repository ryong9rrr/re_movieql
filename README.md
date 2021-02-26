# GraphQL 다시 복습하기

# 변경사항

## Error

- package.json 에 "type": "module" 추가 안할 시 에러

  ⚠ Cannot use import statement outside a module

- 자바스크립트 파일 불러올 때 .js 생략 시 에러

      ⚠
      internalBinding('errors').triggerUncaughtException(Error [ERR_MODULE_NOT_FOUND]: Cannot find module 'C:\Users\yong\Desktop\myProject\re_movieql\graphql\resolvers' imported from C:\Users\yong\Desktop\myProject\re_movieql\index.jsDid you mean to import ../graphql/resolvers.js?  ...js:56:40)  at link (internal/modules/esm/module_job.js:55:36) {  code: 'ERR_MODULE_NOT_FOUND'  }

- "start": "nodemon --exec babel-node index.js" 으로 작성하지 않고

  그냥 "start": "nodemon"만 작성해도 무방
