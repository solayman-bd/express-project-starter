Project setup step by step:

1. npm init -y
2. npm install express
3. npm install mongoose --save
4. npm install typescript --save-dev
5. npm i cors
6. npm i dotenv
7. tsc -init
8. select root dir and out dir in tsconfig.json file
9. npm i --save-dev @types/node
10. npm i --save-dev @types/express
11. add a script in the scripts in package.json to convert typescript code to js code. "build":"tsc"
12. make a folder. src/app.ts, src/server.ts
13. Connect db in server.ts
14. add to tsconfig.json:  
    "include": ["src"], // which files to compile
    "exclude": ["node_modules"], // which files to skip
15. eslint: npm install eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin --save-dev
16. npx eslint --init. Answer the questions according to the preference
17. eslint: https://github.com/ShafiaChy/Eslint-Config-Setup/blob/main/Readme.md?fbclid=IwZXh0bgNhZW0CMTAAAR0yyuOQ2AhN_h4BZwxdvTCgd8g9f_llAnZKq79aRihwTyUhIyZG6ERZHe4_aem_AaRPwdj8vSLY5LQolz-j1ji_mw92-aH0bbTpmmxOEcuBGZ2X4Li-XhNpdYWwfm6Ddf7rmdCKa683fq_rud1ZkUT1
18. npm install --save-dev prettier
19. Make .prettierrc.json file and write rules
20. npm install --save-dev eslint-config-prettier-> remove the confliction between eslint and prettier
