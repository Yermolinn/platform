# DigitalHippo - A Modern Fullstack E-Commerce Marketplace for Digital Products

Built with the Next.js 14 App Router, tRPC, TypeScript, Payload & Tailwind

> [!WARNING]  
> The application utilizes email sending and account verification through the Resend service. Unfortunately, the service only allows sending test emails, and for real emails, an organization's mail is required, which I do not have. The application has a fully prepared verification flow (all pages, logic, and registration). However, for minimal functionality, this was disabled, and the account is verified upon registration.


## Technology Stack
- Next.js 14 (self-hosted using Express server)
- Typescript
- Tailwind CSS
- Express (for self-hosting)
- MongoDB & Mongoose
- [tRPC](https://trpc.io/) (React Query + API Routes + Full TS support)
- [Payload CMS](https://payloadcms.com/)
- Nodemailer
- Sender
- Stripe
- Zustand
- Zod
- React Hook Form
- Railway App (for deployment)

## Features

- 🛠️ Complete marketplace built from scratch in Next.js 14
- 💻 Landing page & product pages
- 💳 Full admin dashboard
- 🛍️ Users can purchase and sell their own products
- 📱  Full responsive for all devices
- 🛒 Locally persisted shopping cart
- 💳 Payment checkout using Stripe
- 🔑 Authentication and CRM system using Payload
- 🖥️ Self-host Next.js (using Express server)
- 🌟 Clean, modern UI using shadcn-ui
- ✉️ Beautiful emails for signing up and after purchase using Nodemailer & Sender
- ✅ Admins can verify products to ensure high quality
- ⌨️ 100% written in TypeScript
- 🎁 ...much more
