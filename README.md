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
8. npx prisma studio

# Upload things

1. we are going to use upload things for saving images.
2. Install => npm install uploadthing @uploadthing/react react-dropzone
3. get api keys from upload thing and paste it in your .env file.

/**\*\*\*\***\*\***\*\*\*\***\***\*\*\*\***\*\***\*\*\*\***/

1. npm install zustand = for modal
2. For copy paste functionality => navigator.clipboard.writeText(inviteUrl);
3. install another package :- npm i query-string

# Socket

1. npm i socket.io - for server
2. npm i socket.io-client - for client (frontend)
3. we are going to old pages structure as next13 has some issues with app router.
4. we are going to create custom types for socket

# Emoji

- npm i emoji-mart @emoji-mart/data @emoji-mart/react

# Chat message component

- we are going to install tanstack query package
