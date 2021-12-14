#instaclone

### #3.1 Apollo Server
- 참고로 graph-yoga는 Apollo 서버 위에서 동작 => 중간 단계 생략 바로 apollo 서버로 감

### #3.2 Babel
- babel : javascript complier
- npm install --save-dev @babel/core
- npm install @babel/preset-env --save-dev
- npm install @babel/node --save-dev

### #3.3 POC API
- ORM : SQL 코드를 쓸 필요 없이 js코드를 작성하면 Prisma가 데이터베이스와 대신 말해줌
### #3.4 Prisma Setup (09:24)
- [recap bot]
- npm install @prisma/cli -D
- npx prisma init
- install porstresapp or pgadmin4
- ** pgadmin4에서 나만의 Login/Group Roles만들기 Privileges 에서 모든 권한 yes해주기