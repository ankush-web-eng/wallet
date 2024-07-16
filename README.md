Clone the repo
GO TO packages/db 
Add the DATABASE_URL to .env
RUN npm install
RUN npx prisma generate
RUN npm run dev

or

RUN docker pull deshwalankush23/wallet
RUN docker run -p 3000:3000 deshwalankush23/wallet //Add environment variables from postgres as DATABASE_URL
