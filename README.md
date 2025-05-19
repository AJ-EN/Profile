# Ayush Jangid - Personal Portfolio & Blog

This is the repository for my personal portfolio website and blog, built with [Next.js](https://nextjs.org/) and [Prismic](https://prismic.io/).

## ✨ Features

*   **Modern Tech Stack:** Next.js 14 (App Router), React, TypeScript.
*   **Headless CMS:** Content managed with Prismic, allowing for easy updates to projects, blog posts, and site settings.
*   **Dynamic Content:** Utilizes Prismic Slices for flexible page building.
*   **Styling:** Styled with [Tailwind CSS](https://tailwindcss.com/) for a utility-first approach.
*   **Animations:** Smooth animations and interactions powered by [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/).
*   **Responsive Design:** Fully responsive for optimal viewing on all devices.
*   **SEO Optimized:** Metadata generated dynamically for better search engine visibility.

## 🛠 Tech Stack

*   **Framework:** [Next.js](https://nextjs.org/) 14 (App Router)
*   **Language:** [TypeScript](https://www.typescriptlang.org/)
*   **CMS:** [Prismic](https://prismic.io/)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
*   **Animation:** [GSAP](https://greensock.com/gsap/)
*   **Font:** Urbanist (via `next/font`)
*   **Deployment:** (e.g., Vercel, Netlify - specify where you plan to deploy)

## 🚀 Getting Started

### Prerequisites

*   Node.js (v18.x or later recommended)
*   npm, yarn, pnpm, or bun

### 1. Clone the repository:

```bash
git clone https://github.com/your-username/profile-of-ayush.git
cd profile-of-ayush
```

### 2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

### 3. Set up Prismic:

*   This project connects to a Prismic repository. You'll need to have one set up with the necessary Custom Types and Slices.
*   The Prismic repository name is configured in `src/prismicio.ts`.

### 4. Environment Variables:

Create a `.env.local` file in the root of the project and add any necessary environment variables. For Prismic, you might need:

```env
# .env.local
NEXT_PUBLIC_PRISMIC_ENVIRONMENT=your-prismic-repo-name
# Add any other environment variables if needed
```
*(Replace `your-prismic-repo-name` with your actual Prismic repository name if it's not already hardcoded or handled by `process.env.NEXT_PUBLIC_PRISMIC_ENVIRONMENT` in `prismicio.ts`)*

### 5. Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📜 Available Scripts

*   `npm run dev`: Starts the development server.
*   `npm run build`: Builds the application for production.
*   `npm run start`: Starts the production server.
*   `npm run lint`: Lints the codebase.
*   `npm run slicemachine`: Starts the Prismic Slice Machine.
*   `npx update-browserslist-db@latest`: Updates the `caniuse-lite` database for Browserslist.

## 🎨 Prismic Slices Used

This project utilizes the following Prismic Slices (located in `src/slices/`):

*   Biography
*   ContentIndex
*   Experience
*   Hero
*   ImageBlock
*   TextBlock
*   *(Add any other slices you have)*

## 🌐 Deployment

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/profile-of-ayush/issues).

## 📄 License

(Specify your license, e.g., MIT)

---

_This README was generated with the help of GitHub Copilot._