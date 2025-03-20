# Canonizer Module: Direct & Delegated Supported Camps

This module is part of the **Canonizer** project, designed to manage user-supported camps effectively.

## Direct Supported Camps

**Direct Supported Camps**: Users personally support a camp, meaning their support directly contributes to the camp's ranking and influence.

The code for the **Direct Supported Camp** page is built using **Next.js**, leveraging **Ant Design (AntD)** components for UI and functionality.

### Key Features:
#### **Ant Design Components Used:**
- **Table**: Displays camp data in a structured format.
- **Button**: Includes a **Primary Button Component** for consistent styling.
- **Pagination**: Manages data navigation.
- **Empty**: Displays when there is no data.
- **Modal**: Used for confirmations or additional actions.
- **Form & Input**: Handles user inputs dynamically.
- **Drawer**: Displays additional content in a side panel.
- **Card**: Organizes information in a visually appealing way.

#### **Dynamic Imports:**
- `next/dynamic` is used to import the draggable component dynamically, ensuring better performance and lazy loading when needed.

#### **Next.js Image Optimization:**
- `next/image` is used for optimized image rendering, improving loading speed and efficiency.

#### **Draggable Feature:**
- Implemented using a dynamically imported draggable component, allowing users to reorder supported camps as needed.

#### **State Management:**
- `useState` is used to manage local component states like modal visibility, input values, and selected camps.
- `useSelector` retrieves global state values from Redux (or any state management library used).

#### **Tailwind CSS for Styling:**
- Used for responsive design, custom styling, and utility-first CSS classes, ensuring a clean and maintainable UI.

---

## Delegated Supported Camps

**Delegated Supported Camps**: Users assign their support to another person, who then decides which camp to support on their behalf. This allows for proxy support, where one user represents multiple voices.

The component is built using **Next.js**, leveraging **Ant Design** for UI elements and state management to create a structured and interactive user interface.

### Key Features:
#### **Ant Design Components Used:**
- **Table**: Displays data in a structured format.
- **Modal**: Handles confirmations or alerts.
- **Button**: Includes a **Primary Button Component** for consistent UI.
- **Form & Input**: Captures user input dynamically.
- **Pagination**: Enables navigation through data.
- **Empty**: Displays when no data is available.
- **Card**: Organizes elements visually.
- **Row & Col**: Manages a responsive grid layout.

#### **Next.js Features:**
- `next/image`: Used for optimized image rendering, improving performance and loading speed.

#### **State Management & Effects:**
- Uses `useState` to manage component states like modal visibility, form values, and table data.
- Uses `useEffect` to handle side effects such as data fetching or state updates.

---


