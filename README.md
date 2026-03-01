# NextFlow-app
Hk project

## Getting Started

Follow these steps to run the project after cloning:

1. **Clone the repository**
   ```sh
   git clone https://github.com/blaxeisworking/NextFlow-app.git
   cd NextFlow-app
   ```

2. **Install dependencies**
   ```sh
   npm install
   ```

3. **Copy environment variables**
   ```sh
   cp .env.example .env.local
   ```
   Edit `.env.local` and add:
   ```
   CLERK_SECRET_KEY=sk_test_HQWpX9GiDWyJ8HKlftptXeaR6N2SwXIFcAhhDKUofV
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_ZnVubnktamFndWFyLTQxLmNsZXJrLmFjY291bnRzLmRldiQ
   ```
   Fill in any other required secrets.

4. **Set up the database**
   ```sh
   npx prisma generate
   npx prisma migrate dev
   ```

5. **Run the development server**
   ```sh
   npm run dev
   ```

6. **Open the app**
   Visit [http://localhost:3000](http://localhost:3000) in your browser.
