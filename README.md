- first setup your project using shadcn
- depending on which style we use of shadcn we gonna have different icons.
- for authentication we gonna follow clerk docs.
- for theme install an package called next-theme.

# Database :-

1. npm i -D prisma
2. npx prisma init
3. @db.Text is basically used for long string
4. npx prisma generate
5. npx prisma db push
6. npm i @prisma/client
7. In Production, To prevent hot reload we gonna declare global variable to store our database client.

# Upload things

1. we are going to use upload things for saving images.
2. Install => npm install uploadthing @uploadthing/react react-dropzone
3. get api keys from upload thing and paste it in your .env file.

/********\*\*********\*********\*\*********/

1. npm install zustand = for modal
2. For copy paste functionality => navigator.clipboard.writeText(inviteUrl);
3. install another package :- npm i query-string
