# NextStepper - Land Your Next Step to Your Dream Career

Welcome to **NextStepper** – your ultimate career development platform! Whether you're looking for the latest job trends, preparing for interviews, or crafting the perfect resume and cover letter, NextStepper has you covered.

---

## 🚀 Features
- **Trending Job Roles** – Discover roles that match your interests.
- **Interview Preparation** – Get AI-powered interview questions and answers.
- **Resume & Cover Letter Builder** – Create professional documents effortlessly.
- **Personalized Experience** – Tailored career insights after onboarding.

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/nextstepper.git
cd nextstepper
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the project root and add the following:
```env
DATABASE_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```
> ⚠️ Make sure to fill in the required API keys before running the project.

### 4️⃣ Set Up the Database (Prisma)
```sh
npx prisma migrate dev
```

### 5️⃣ Start Inngest Dev Server
```sh
npx inngest-cli@latest dev
```

### 6️⃣ Run the Development Server
```sh
npm run dev
```
Now, open [http://localhost:3000](http://localhost:3000) to explore NextStepper!

---

## 📦 Deployment
To build the project for production, run:
```sh
npm run build
```
Deploy your project on **Vercel, AWS, or any Next.js-supported platform**.

---

## 🤝 Contributing
We welcome contributions! Feel free to open an issue or submit a pull request.

---


Happy coding! 🚀

