# KitCord

Welcome to KitCord, a powerful real-time messaging platform built with the latest web technologies. This repository houses the codebase for KitCord, utilizing an impressive tech stack including Next.js 13, React, Socket.io, Prisma, Tailwind, and MySQL. Explore the feature-rich environment designed to elevate your communication experience.

## Features

- **Real-time Messaging**: Utilizing Socket.io to provide seamless and instant communication.
- **Attachment Support**: Send attachments as messages with ease using UploadThing.
- **Edit and Delete in Real-time**: Empowering users with the ability to edit and delete messages in real-time.
- **Multimedia Channels**: Create text, audio, and video call channels effortlessly.
- **1:1 Conversations**: Engage in private conversations with other members.
- **Video Calls**: Enjoy face-to-face interactions with 1:1 video calls.
- **Member Management**: Take control with features like kicking members and role changes (Guest/Moderator).
- **Invite System**: Generate unique invite links for a fully functional invite system.
- **Infinite Loading**: Smoothly load messages in batches of 10 for a seamless user experience (tanstack/query).
- **Server Customization**: Create and customize servers to meet your unique needs.
- **Beautiful UI**: Aesthetic appeal brought to you by TailwindCSS and ShadcnUI.
- **Responsivity**: Experience full responsiveness with a thoughtfully crafted mobile UI.
- **Light/Dark Mode**: Choose between light and dark modes to suit your preferences.
- **Websocket Fallback**: Seamless fallback to polling with alerts in case of websocket issues.
- **ORM Using Prisma**: Efficient Object-Relational Mapping (ORM) with Prisma.
- **MySQL Database**: Leveraging the power of MySQL, hosted on PlanetScale.
- **Authentication with Clerk**: Secure and streamlined authentication process powered by Clerk.

## Prerequisites

Ensure you have Node.js version 18.x.x installed before proceeding.

## Installation

```shell
npm install

```
## .ENV Setup  

```shell
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

## Setup Prisma

```shell
npx prisma generate
npx prisma db push
```

## Start Project

```shell
npm run dev
```
