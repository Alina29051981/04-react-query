# Movie Search App

is a modern React application built with Vite + TypeScript that allows you to search movies via TMDB API, display them in a grid, open detailed modals, and supports pagination.

The project uses best practices in React, TypeScript type safety, state management with TanStack Query, and a clean component structure with CSS modules.

# Project Features

- Movie Search

Users can search for movies using a clean and intuitive search interface.

Input validation ensures meaningful search queries, with clear error messages for empty or invalid input.

- Movie Display

Movies are displayed in a responsive grid with posters and titles.

Clicking on a poster opens a modal with detailed information about the movie.

Smooth user experience with focus on usability and accessibility.

- Pagination

Supports browsing multiple pages of search results.

Pagination is rendered only when more than one page of results is available.

Users can easily navigate between pages while maintaining search context.

- Data Fetching and State Management

Fetches movie data efficiently and stores it for quick access.

Handles loading states, error states, and cached data seamlessly.

Application state is well-structured and type-safe.

- User Experience

Loading indicators and error messages provide clear feedback to users.

Modals can be closed via multiple interactions (clicking outside, pressing Escape, or using a close button).

Clean and organized interface for a smooth and intuitive experience.

- Type Safety

All data structures and component props are strictly typed.

Ensures consistent and predictable behavior across the application.

- Styling

Modular, reusable styles to keep components isolated and maintainable.

Responsive layout and accessible design for various devices and screen sizes.

# Technologies Used

Frontend: React 19, Vite, TypeScript

State & Data Fetching: TanStack Query, React state

HTTP Requests: Axios

Pagination: React Paginate

UI/UX: CSS Modules, modern-normalize, react-hot-toast

Deployment: Vercel
