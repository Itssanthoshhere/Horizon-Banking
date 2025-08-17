<div align="center">
  <br />
     <img src="https://github.com/adrianhajdin/banking/assets/151519281/3c03519c-7ebd-4539-b598-49e63d1770b4" alt="Project Banner">
    </a>
  <br />
  
  <div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
  </div>

  <h3 align="center">🏦 Horizon Banking – A Modern Fintech App</h3>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)  
2. ⚙️ [Tech Stack](#tech-stack)  
3. 🔋 [Features](#features)  
4. 🤸 [Quick Start](#quick-start)  
5. 📞 [Contacts](#contacts)
6. 🚀 [Show Your Support](#show-your-support) 


## <a name="introduction">🤖 Introduction</a>

Built with Next.js, Horizon is a financial SaaS platform that connects to multiple bank accounts, displays transactions in real-time, allows users to transfer money to other platform users, and manages their finances altogether. 

## <a name="tech-stack">⚙️ Tech Stack</a>

- **Framework:** Next.js 14, React, TypeScript  
- **Styling:** Tailwind CSS, ShadCN UI  
- **Payments:** Dwolla API  
- **Forms & Validation:** React Hook Form + Zod  
- **Charts & UI:** Chart.js  

## 🎨 UI/UX Design

The **Horizon Banking App** UI was crafted with a **minimal, modern, and finance-focused design system**.  
From the dashboard overview to transaction history and fund transfers, every screen is designed to ensure **clarity, trust, and ease of use** for users managing their money.

<p align="center">
  <a href="https://www.figma.com/design/MPswLezMU8gQ0qQEHCtD1U/Horizon-Banking-App?node-id=2-2&t=eWEevEqQCzaS8sXV-1" target="_blank">
    <img src="https://img.shields.io/badge/View%20Figma%20Design-blue?style=for-the-badge&logo=figma&logoColor=white" alt="Figma Link" />
  </a>
</p>


## <a name="features">🔋 Features</a>

👉 **Authentication**: An ultra-secure SSR authentication with proper validations and authorization

👉 **Connect Banks**: Integrates with Plaid for multiple bank account linking

👉 **Home Page**: Shows general overview of user account with total balance from all connected banks, recent transactions, money spent on different categories, etc

👉 **My Banks**: Check the complete list of all connected banks with respective balances, account details

👉 **Transaction History**: Includes pagination and filtering options for viewing transaction history of different banks

👉 **Real-time Updates**: Reflects changes across all relevant pages upon connecting new bank accounts.

👉 **Funds Transfer**: Allows users to transfer funds using Dwolla to other accounts with required fields and recipient bank ID.

👉 **Responsiveness**: Ensures the application adapts seamlessly to various screen sizes and devices, providing a consistent user experience across desktop, tablet, and mobile platforms.

and many more, including code architecture and reusability. 

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/Itssanthoshhere/Horizon-Banking.git
cd banking
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#NEXT
NEXT_PUBLIC_SITE_URL=

#APPWRITE
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://fra.cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

#PLAID
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

#DWOLLA
DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox

```

Replace the placeholder values with your actual respective account credentials. You can obtain these credentials by signing up on the [Appwrite](https://appwrite.io/?utm_source=youtube&utm_content=reactnative&ref=JSmastery), [Plaid](https://plaid.com/) and [Dwolla](https://www.dwolla.com/)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.


---

## 🙌 Special Thanks

Inspired by **JavaScript Mastery’s** tutorials, but built with my own improvements, custom UI, and bug fixes.

---

## <a name="contacts">🔗 Contacts</a>

Feel free to connect with me:

* GitHub: [Itssanthoshhere](https://github.com/Itssanthoshhere)
* LinkedIn: [Santhosh VS](https://www.linkedin.com/in/thesanthoshvs/)

---

## ⭐️ Show Your Support

If you liked this project, drop a ⭐ on the repo and share it with others!



