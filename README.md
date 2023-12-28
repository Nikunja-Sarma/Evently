# lol

[https://camo.githubusercontent.com/db50fa0fc92b74e69382827a28caa8949d30252f3285c8de0b6e9e0075405b42/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4e6578745f4a535f31342d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f436f6c6f723d7768697465266c6f676f3d6e657874646f746a7326636f6c6f723d303030303030](https://camo.githubusercontent.com/db50fa0fc92b74e69382827a28caa8949d30252f3285c8de0b6e9e0075405b42/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4e6578745f4a535f31342d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f436f6c6f723d7768697465266c6f676f3d6e657874646f746a7326636f6c6f723d303030303030)

[https://camo.githubusercontent.com/307513cbb47e2b6602e16e116d21f9c7ddad4fab09985e27857f213c41646aeb/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d547970655363726970742d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f436f6c6f723d7768697465266c6f676f3d7479706573637269707426636f6c6f723d333137384336](https://camo.githubusercontent.com/307513cbb47e2b6602e16e116d21f9c7ddad4fab09985e27857f213c41646aeb/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d547970655363726970742d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f436f6c6f723d7768697465266c6f676f3d7479706573637269707426636f6c6f723d333137384336)

[https://camo.githubusercontent.com/513db702dd35f0a645f26c3fa93ca15ffd075b0e70a7bc5ede4267ac343679ab/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d5374726970652d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f436f6c6f723d7768697465266c6f676f3d73747269706526636f6c6f723d303038434444](https://camo.githubusercontent.com/513db702dd35f0a645f26c3fa93ca15ffd075b0e70a7bc5ede4267ac343679ab/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d5374726970652d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f436f6c6f723d7768697465266c6f676f3d73747269706526636f6c6f723d303038434444)

### A Full Stack Next 14 Events App! [Evently](https://evently-gamma-hazel.vercel.app)

## 📋 Table of Contents

1. 🤖 [Introduction](https://github.com/adrianhajdin/event_platform#introduction)
2. ⚙️ [Tech Stack](https://github.com/adrianhajdin/event_platform#tech-stack)
3. 🔋 [Features](https://github.com/adrianhajdin/event_platform#features)
4. 🤸 [Quick Start](https://github.com/adrianhajdin/event_platform#quick-start)

## 🤖 Introduction

Built on Next.js 14, the events application stands as a comprehensive, full-stack platform for managing events. It serves as a hub, spotlighting diverse events taking place globally. Featuring seamless payment processing through Stripe, you have the capability to purchase tickets for any event or even initiate and manage your own events.

If you're getting started and need assistance or face any bugs, join our active Discord community with over 27k+ members. It's a place where people help each other out⚙️ Tech Stack

- Node.js
- Next.js
- TypeScript
- TailwindCSS
- Stripe
- Zod
- React Hook Form
- Shadcn
- uploadthing

## 🔋 Features

👉 **Authentication (CRUD) with Clerk:** User management through Clerk, ensuring secure and efficient authentication.

👉 **Events (CRUD):** Comprehensive functionality for creating, reading, updating, and deleting events, giving users full control over event management.

- **Create Events:** Users can effortlessly generate new events, providing essential details such as title, date, location, and any additional information.
- **Read Events:** Seamless access to a detailed view of all events, allowing users to explore event specifics, including descriptions, schedules, and related information.
- **Update Events:** Empowering users to modify event details dynamically, ensuring that event information remains accurate and up-to-date.
- **Delete Events:** A straightforward process for removing events from the system, giving administrators the ability to manage and curate the platform effectively.

👉 **Related Events:** Smartly connects events that are related and displaying on the event details page, making it more engaging for users

👉 **Organized Events:** Efficient organization of events, ensuring a structured and user-friendly display for the audience, i.e., showing events created by the user on the user profile

👉 **Search & Filter:** Empowering users with a robust search and filter system, enabling them to easily find the events that match their preferences.

👉 **New Category:** Dynamic categorization allows for the seamless addition of new event categories, keeping your platform adaptable.

👉 **Checkout and Pay with Stripe:** Smooth and secure payment transactions using Stripe, enhancing user experience during the checkout process.

👉 **Event Orders:** Comprehensive order management system, providing a clear overview of all event-related transactions.

👉 **Search Orders:** Quick and efficient search functionality for orders, facilitating easy tracking and management.

and many more, including code architecture and reusability

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- yarn (Node Package Manager)

**Cloning the Repository**

```
git clone https://https://github.com/Nikunja-Sarma/evently
cd evently
```

**Installation**

Install the project dependencies using yarn:

```
yarn
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```
#NEXT
NEXT_PUBLIC_SERVER_URL=https://evently-gamma-hazel.vercel.app

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#MONGODB
MONGODB_URI=

#UPLOADTHING
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

#STRIPE

STRIPE_WEBHOOK_SECRET
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
```