# ๐ ํ๋ก์ ํธ์ ์คํ ๋ฐฉ๋ฒ

```
npm install

npm start
```

# ๐ ํด๋ ๊ตฌ์กฐ ์ค๋ช
api ํด๋
/auth

authํด๋ ์์๋ ํ์๊ฐ์๊ณผ ๋ก๊ทธ์ธ๊ณผ ๊ด๋ จ๋ axios์ฝ๋๋ค์ด ์์ต๋๋ค.

/todo

todoํด๋์๋ todo๊ฐ์ ธ์ค๊ธฐ, todo์์ , todo์ญ์ , todo๋ง๋ค๊ธฐ axios์ฝ๋๊ฐ ์์ต๋๋ค.

components ํด๋
/auth

์ด๋ฉ์ผ๊ณผ ํจ์ค์๋๋ฅผ ์๋ ฅ๋ฐ๋ AuthForm ํ์ผ์ด ์์ต๋๋ค.

/todo

์๋ก์ด todo๋ฅผ ์์ฑ๋ฐ๋ TodoForm์ด ์์ต๋๋ค.

todo๋ฅผ ๋ฐ์์์ ๋ณด์ฌ์ฃผ๋ TodoList๊ฐ ์์ต๋๋ค.

todo๋ฅผ ์๋ฐ์ดํธ ๋ฐ๋ ์์  ์ฐฝ์ธ TodoUpdateForm์ด ์์ต๋๋ค.

router ํด๋
๋ผ์ฐํฐ ํด๋์๋ ๊ฐ๊ฐ ํ๋์ ํ์ด์ง์ธ Todoํ์ผ๊ณผ Authํ์ผ์ด ์์ต๋๋ค.
types ํด๋
types ํด๋์๋ todoํ์ผ์ด ์กด์ฌํ๋๋ฐ Todo๊ฐ์ฒด์ ํ์๊ณผ updateํ๋๋ฐ ํ์ํ

todo์ isCompletedํ์์ด ์กด์ฌํฉ๋๋ค

# ๐ tree

```
src
 โฃ api
 โ โฃ auth.ts
 โ โฃ interceptor.ts
 โ โ todo.ts
 โฃ components
 โ โฃ auth
 โ โ โ AuthForm.tsx
 โ โ todo
 โ โ โฃ TodoForm.tsx
 โ โ โฃ TodoList.tsx
 โ โ โ TodoUpdateForm.tsx
 โฃ router
 โ โฃ Auth.tsx
 โ โ Todo.tsx
 โฃ style
 โ โฃ AuthStyle.js
 โ โฃ GlobalStyle.js
 โ โ TodoStyle.js
 โฃ types
 โ โ todo.ts
 โฃ utils
 โ โ tokenProvider.ts
 โฃ App.tsx
 โฃ index.tsx
 โฃ react-app-env.d.ts
 โฃ reportWebVitals.ts
 โ setupTests.ts
```

# ๋ฐฐํฌ ์ฃผ์

https://wanted-pre-onboarding-fe-6-1-1.vercel.app/

# Best practice

https://github.com/wanted-fe-6/wanted-pre-onboarding-fe-6-1-1/wiki
