> [!NOTE]
> **Repo contents:** Has backend and frontend.<br>
> **Purpose of repo:** To deploy backend for this module.<br>
> **Tasks in module:** To implement frontend.

# Module: QKart Frontend (Hooks)

## Overview of Module

### QKart

QKart is an E-commerce application offering a variety of products for customers to choose from.

During the course of this project:

- Implemented the core logic for authentication, shopping cart, and checkout.
- Improved UI by adding responsive design elements for a uniform experience across different devices.
- Utilized REST APIs to dynamically load and render data served by the backend server.
- Deployed the website to Netlify/Vercel.

<br>

<div align="center"> 
<img src="https://directus.crio.do/assets/1034488f-e6c8-4489-bb93-4265fd12fc11?" width="50%" >
<p align="center">QKart Component Architecture</p>
</div>

<br>

<div align="center"> 
<img src="https://directus.crio.do/assets/69a039c9-4499-424f-b66c-bc918c32a891?" width="50%" >
<p align="center">QKart Shopping Interface (Products page)</p>
</div>

## My Tasks

1. **Adding frontend features for**:
   - Authentication
   - Dynamic product listing
   - Search
   - Shopping cart
   - Checkout process
2. **Deployment**

## Milestones

### 1. Add Registration Feature

- **Scope of work**:
  - Implemented logic and used backend API to get the registration feature ready.
  - Added validation for the registration form user input values to display informative error messages.
- **Skills used**:
  - React.js, Event Handling, Forms, React Hooks, REST API, Error Handling

### 2. Implement Registration-Login Flow and Set Up Routing

- **Scope of work**:
  - Used React Router library to set up routes in the application and redirect customers to appropriate pages.
  - Added UI and logic to get the Login page ready.
  - Stored user information at client side using localStorage to avoid login on revisit.
- **Skills used**:
  - React Router, Material UI, localStorage, Controlled Components, Conditional Rendering

<br>

<div align="center"> 
<img src="https://directus.crio.do/assets/e7fffbe8-0d6b-4b82-a353-42787b551cda?" width="50%" >
<p align="center">Request-response cycle for QKart User signup and login</p>
</div>
<br>
<div align="center"> 
<img src="https://directus.crio.do/assets/e049e742-f405-4e09-9bf0-5db1fd7a07bc?" width="50%" >
<p align="center">User flow on website for signup and login</p>
</div>



### 3. Display Products and Implement Search Feature

- **Scope of work**:
  - Utilized the `useEffect()` hook to fetch products data after DOM is rendered for faster page loading.
  - Added search bar to display only on the Products page’s header and implemented search logic.
  - Implemented debouncing for improved UX and reduced API calls on search.
- **Skills used**:

  - Keyword Search, Debouncing, Material UI Grid

<br>
<div align="center"> 
<img src="https://directus.crio.do/assets/ff900517-2e55-454d-9419-25bd4ce4db49?" width="50%" >
<p align="center">QKart Products page</p>
</div>


### 4. Add Shopping Cart and Implement Checkout Flow

- **Scope of work**:
  - Added Cart to Products page and made it responsive.
  - Made authenticated POST API calls to implement Cart logic.
  - Rendered Cart with differing designs in Products page and Checkout page using conditional rendering.
  - Implemented UI and logic to add and select new addresses.
- **Skills used**:

  - Responsive Design, Reusable Components

<br>
<div align="center"> 
<img src="https://directus.crio.do/assets/cee7a520-32d5-4fd1-9661-c5e257f1b98d?" width="50%" >
<p align="center">Products page UI with responsive Cart design (Left: Desktop, Right: Mobile)</p>
</div>
<br>
<div align="center"> 
<img src="https://directus.crio.do/assets/58527646-a8d2-4d39-ae15-5356da347459?" width="50%" >
<p align="center">QKart Checkout page</p>
</div>


### 5. Deploy the QKart Website

- **Scope of work**:
  - Deployed the QKart React app to Netlify.
  - Configured Netlify to support visiting any subpages directly as React is a single-page application.
- **Skills used**:
  - Deployment, Netlify
