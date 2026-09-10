## Connect NestJ with Prisma and Neon

#### Create Project
```bash
nest new my-nest
```
```bash
cd my-nest
```
---

>#### Neon e project create koro and then database connect koro and example.env te paste koro.
<img width="1597" height="762" alt="image" src="https://github.com/user-attachments/assets/bf2fd0be-b6c5-4f60-9b5b-15ef35768385" />


#### `example.env`
```bash
DATABASE_URL=''
```
---

#### Prisma install
```bash
npm install prisma --save-dev
```
```bash
npm install @prisma/client
```
```bash
npm install -D prisma@7.10.0
```
```bash
npx prisma init
```
---


>#### Note: jodi prisma/schema.prisma and .env file create na hoi tahole menualy create koro
```bash
New-Item .env
```
```bash
mkdir prisma
```
```bash
New-Item prisma/schema.prisma
```
---

#### `.env`
>#### example.env file theke DATABASE_URL copy kore paste kore daw.
```bash
DATABASE_URL=''
```
---
