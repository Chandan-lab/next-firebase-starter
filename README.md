# Next.js + Firebase Setup
Full Starter Code for Next.js and Firebase 👤 `next-firebase-auth` + 🗃 Firestore + 🔔 Messaging.

## What's Provided?
* Firebase Authentification Setup
* Automatically set new users in `users` collection 
* Firebase Client and Admin SDK Init
* Clean Project Structure (Functions, references for Firestore)
* Server Side Rendering via Firestore Data
* Enable Firebase Cloud Messaging 
* FCM Service Worker Setup

## ✅ Getting Started

Install dependencies `npm install`

* ### 🏡 Environment Vaiables
    Refer `.env.local.example` and rename after adding your own variables.

* ### 🔓 Private and Login Pages
    Refer `pages/dashboard.js` for private page (Authentication Required). And `pages/login.js` for login page.

* ### 🔑 Setting Custom Auth Providers
    Refer [`firebaseAuth.js`](https://github.com/shreyas-jadhav/next-firebase-starter/blob/main/components/elements/FirebaseAuth.js) file to add more Providers. 

* ### 📄 Adding users into firestore collection
    Refer - [`firebaseAuth.js` callbacks](https://github.com/shreyas-jadhav/next-firebase-starter/blob/29bc5278439e8fe98c932b067ffc55ca91b48677/components/elements/FirebaseAuth.js#L32)

* ### 💻 SSR / SSG using Firestore Data
    Use [Admin SDK's Firestore Functions](https://github.com/shreyas-jadhav/next-firebase-starter/blob/main/utils/firebase/firestore/fsAdminFunctions.js) for server operations. 

    **Note:** Do not use these for Client Side.

* ### 🚚 Absolute Imports
    Refer [jsconfig.json](https://github.com/shreyas-jadhav/next-firebase-starter/blob/29bc5278439e8fe98c932b067ffc55ca91b48677/jsconfig.json#L5) 

* ### 👩‍🏭 Firebase Cloud Messaging service worker
    Refer [firebase-messaging-sw.js](https://github.com/shreyas-jadhav/next-firebase-starter/blob/main/public/firebase-messaging-sw.js)


## Additional Docs
* `next-firebase-auth` library [documentation](https://github.com/gladly-team/next-firebase-auth) (Great Library ♥)
* [Firebase Official Documentation](https://firebase.google.com/docs/firestore)



## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
