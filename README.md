# Next.js Dashboard with Data Fetching

This project is a Next.js application that implements a dashboard for displaying opportunities fetched from an API. It includes dynamic routing, state management, and reusable components.

## Features

- **Dynamic Routing**: Uses Next.js dynamic routes to display specific opportunities based on the URL parameter.
- **Data Fetching**: Fetches data from a backend API using a custom `useFetchData` hook.
- **State Management**: Manages state using React's `useState` and `useEffect` hooks.
- **Reusable Components**: Includes reusable components for displaying job details, responsibilities, categories, and more.
- **TypeScript Support**: Fully typed with TypeScript for better developer experience and type safety.
- **FontAwesome Integration**: Uses FontAwesome icons for a visually appealing UI.
- 
 the populated cards 
![Screenshot (57)](https://github.com/user-attachments/assets/a0781657-867f-4541-bdaa-87a0ae56a7c0)

 the list 
![Screenshot (59)](https://github.com/user-attachments/assets/97a1965d-bf14-41ac-92b2-5782cfa0ceaf)
file structure
c:\Users\NEZHAB\Desktop\Next js fetching with next js\

### File Structure

```plaintext
src/
├── app/
│   ├── dashboard/
│   │   ├── [index]/
│   │   │   └── page.tsx        # Main dashboard page
│   ├── component/
│   │   ├── jobs/
│   │   │   └── jobs.tsx       # Reusable job component
│   │   ├── type/
│   │   │   └── type.tsx       # TypeScript interfaces for data models
│   ├── fetchdata/
│   │   └── fetchdata.tsx      # Custom hook for fetching data
├── styles/                     # Global styles (if applicable)
├── public/                     # Static assets (if applicable)
└── README.md                   # Project documentation
```

---

### Technologies Used

1. **Next.js**: Framework for SSR and SSG.
2. **React**: UI library for building components.
3. **TypeScript**: For type safety.
4. **FontAwesome**: Icon library.
5. **Tailwind CSS**: Utility-first CSS framework.
6. **Custom Hooks**: `useFetchData` for API calls.
7. **REST API**: Fetches data from  https://akil-backend.onrender.com.

Let me know if you need further details!
