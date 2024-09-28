# room-listing-app

## Objective: This task will evaluate your ability to write clear, efficient, maintainable, and scalable
code. You will be tested on your approach to structuring a React application, optimizing
performance, and ensuring that the solution can scale as the application grows.
Challenge:
Build a Responsive (Support to both mobile & desktop) room listing page with Infinite loading
capabilities.
## Requirements:
### Technologies:
* Use React JS for building the component.
* Styling can be done using CSS/SCSS (optionally, you can use a CSS
framework like Tailwind CSS or Bootstrap).
* Use React hooks/Redux for managing state.

## Core Features:
* Room Listing Component:
* Create a reusable React component that displays a list of rooms.
* Each room item should include details like the room name, price,
image, videos and description.
* Media files (images or videos) should load efficiently based on user
interaction and viewport visibility.

## Video Optimization:
* Videos should only load or autoplay when they are visible on the
screen and should pause when they leave the viewport.
* Ensure videos are not unnecessarily loaded while the user is scrolling
through the room listings.

## Image Optimization:
* Apply techniques such as image compression, responsive image
loading (using srcset or similar), and lazy loading to optimize
performance.

## Placeholder or Skeleton Loading:
* While images and videos are being fetched, display a placeholder or
skeleton to maintain user experience.

## Infinite Scrolling:
* Implement infinite scrolling so that additional room data loads
automatically as the user scrolls down the page.
* You will be using static JSON data that simulates large data volumes
(suggested: 100+ items for testing).

## Loading Indicator:
* Include a loading spinner or placeholder elements that appear while
fetching new data.

## Error Handling:
* Gracefully handle errors (e.g., failed data fetch) and display
appropriate feedback to the user.

## Scalability Considerations:
* Efficient Resource Loading:
* Prevent the preloading of off-screen media. Only load images and
videos as the user scrolls closer to them.
* Use debouncing or throttling to prevent excessive network requests
during user interactions (e.g., scrolling).

## Memoization:
* Use useMemo or React.memo where appropriate to prevent
unnecessary re-renders of media components.

## Lazy Loading for Other Components:
* Implement lazy loading for images and videos. Media should only load
when it is in or near the user’s viewport (use intersection observer,
native HTML attributes, or a third-party library).
* Besides media, ensure any heavy components are lazily loaded to
improve performance.

## Code Structure: Design the component to be easily extendable. It should be
reusable across different parts of a larger application.
* Data Handling: Ensure efficient handling of large datasets with
pagination-like data fetching to avoid performance issues.

## Deliverables:
* Code:
* Provide access to your GitHub repository with the project.
* Ensure your code is clean, modular, and documented with appropriate
comments.
* Include a README.md file explaining the project setup, architecture, and any
performance optimization strategies you applied.
