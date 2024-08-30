# Spotify Clone

![Spotify Clone](https://img.shields.io/badge/Spotify-Clone-green?style=for-the-badge)

A feature-rich Spotify clone built with Next.js, Supabase, and TypeScript. This application allows users to browse, play, and upload songs, manage their playlists, and enjoy a modern music streaming experience.

![spotify](https://github.com/user-attachments/assets/249ec6ff-0e0f-44b9-8135-f177859e1686)
![spotify-login](https://github.com/user-attachments/assets/43ecc5bb-5c36-4093-b42c-6d0dc8f29c0e)

## Features

- 🎵 **Music Playback**: Play songs directly in the browser with seamless audio streaming.
- 📚 **Music Library**: Browse and manage a collection of songs.
- 🔍 **Search**: Search for songs by title, artist, or genre.
- 💾 **Upload Songs**: Authenticated users can upload their own songs.
- 🔒 **User Authentication**: Secure authentication with Supabase.
- 🎨 **Responsive UI**: Beautiful and responsive design using Tailwind CSS.
- 📊 **Subscription Management**: Manage user subscriptions using Stripe.

## Technologies Used

The Spotify clone leverages a variety of modern technologies to deliver a seamless music streaming experience. Below is a detailed list of the key technologies and tools used in this project:

- **[Next.js](https://nextjs.org/)**: A React framework for server-side rendering and static site generation. It provides a powerful routing system, optimized performance, and developer-friendly features.
- **[Supabase](https://supabase.com/)**: An open-source Firebase alternative that provides a complete backend solution, including a PostgreSQL database, real-time subscriptions, user authentication, and file storage.
- **[React](https://reactjs.org/)**: A JavaScript library for building user interfaces. React's component-based architecture and hooks make it easy to build reusable UI components and manage state effectively.
- **[Tailwind CSS](https://tailwindcss.com/)**: A utility-first CSS framework that allows you to build custom designs directly in your markup. It provides a highly customizable and responsive design system.
- **[Zustand](https://zustand.surge.sh/)**: A small, fast, and scalable state management solution for React. Zustand is used for managing global states, such as the visibility of modals in the application.
- **[React Hot Toast](https://react-hot-toast.com/)**: A lightweight and customizable toast notification library for React. It provides easy-to-use APIs for showing success, error, and informational messages.
- **[Stripe](https://stripe.com/)**: A powerful and secure payment processing platform. Stripe is integrated to manage subscriptions and handle payments securely.
- **[React Icons](https://react-icons.github.io/react-icons/)**: A collection of popular icons as React components. This library is used to add scalable vector icons to the application for better UI/UX.

Each of these technologies has been carefully chosen to provide a robust, scalable, and maintainable codebase, allowing for a rich feature set and a smooth user experience.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/spotify-clone.git
   cd spotify-clone

2. Install the dependencies:

```
npm install
# or
yarn install
```

3. Environment Variables

Create a .env.local file in the root directory and add your environment variables:

```
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
NEXT_PUBLIC_STRIPE_PUBLIC_KEY=your-stripe-public-key
STRIPE_SECRET_KEY=your-stripe-secret-key
```

Replace the placeholders with your actual Supabase and Stripe credentials.

4. Running Locally

Start the development server:

```
npm run dev
# or
yarn dev
```

Open `http://localhost:3000` in your browser to see the application.
