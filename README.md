# Full stack Application for EVVENT
This Application is an authenticated Todo app with TRPC, Next.js, Prisma, Tailwind.
The app uses optimistic updates for all mutations.
Auth is via magic link email.

- [Next.js](https://nextjs.org)
- [NextAuth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [Tailwind CSS](https://tailwindcss.com)
- [tRPC](https://trpc.io)

For using the app make sure all dependencies are installed with an 'npm i' in the project terminal
Then you can start the app typing 'npm run dev' and Ctrl + Click in the url: http://localhost:3000 
after entering the email and in the confirmation page the link is sent to the console back in the project terminal
where 'npm run dev' ran. Ctrl + Click and it'll send you back to the app and you'll be able to use it
(The idea is to send the link to the email provided by the user through an automatic email sending service)
The netlify version can't do this email auth
