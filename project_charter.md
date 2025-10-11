# Project Charter
## Bike Website

### 1. Introduction

This project is about building a bike website where customers can easily explore, compare, and buy bikes online. The goal is to make bike shopping simple, smooth, and enjoyable. Instead of visiting different stores, users can find everything in one place from viewing detailed specs and customer reviews to checking real-time stock and booking test rides. The website focuses on helping customers make better decisions by giving them all the information and tools they need. It’s designed to look modern, work fast, and make the online bike shopping experience stress-free.

---

### 2. Overview and Objectives

### Overview
The Bike Website serves as a complete e-commerce solution for bike enthusiasts. It includes key functionalities such as browsing bikes by category, filtering by price or brand, comparing multiple models side-by-side, reading reviews, booking test rides, and tracking orders. The system also integrates smart personalization like recommending bikes based on browsing history and offers secure checkout options to ensure a trustworthy shopping experience.

### Objectives
- **Enhance User Experience**: Provide easy navigation and interactive features such as filters, search, and comparison tools.
- **Support Informed Decision-Making**: Offer detailed bike specifications, customer reviews, and comparison options.
- **Ensure Secure Transactions**: Implement safe and convenient payment methods for customers.
- **Promote Customer Engagement**: Enable wishlist saving, personalized recommendations, and order notifications.
- **Improve Accessibility**: Include dealer pages, test ride bookings, and real-time inventory updates.
- **Streamline Order Management**: Allow customers to create accounts, track orders, and manage returns or service requests.

---

### 3. Milestones

#### 3.1. Project Planning and Technology Selection
- **Define Technology Stack**
  - Frontend: React, CSS
  - Backend: Node.js, Express.js
  - Database: MongoDB
  - Hosting/Domain: Netlify
 
- **Finalize Development Tools**
  - Design & Prototyping: Figma
  - Collaboration & Testing: MS Teams
 
#### 3.2. Frontend Development
- **Design UI/UX:**
  - Create wireframes in Figma
  - Design pages: Home, Product Listing, Product Details, Cart, Checkout, Returns/Service

- **Implement Static Test Pages**
  - Develop React components for static pages
  - Test layout and styling with CSS

- **Add Interactive Features**
  - Shopping cart functionality
  - Product filtering/sorting
  - Add-to-cart and remove-from-cart actions

#### 3.3. Backend Development
- **Set Up Node.js + Express Server**
  - Create API endpoints for products, cart, orders, and returns
  - Test APIs in development environment

- **Database Integration**
  - Store product information, inventory, and orders in MongoDB
  - Implement CRUD operations for products, promotions, and order management

- **Backend Testing**
  - Ensure correct handling of orders, returns, and inventory updates

#### 3.4. Features & Tools
- **Product Management**
  - Admin interface for adding/editing bikes
  - Set promotions, weekly price changes, and final sale items

- **Customer Order Management**
  - Allow customers to place orders, select pickup/delivery, and pay
  - Handle out-of-stock products with substitutions

- **Returns & Service Requests**
  - Enable customers to request returns or services

- **Cart & Checkout System**
  - Add multiple bikes to cart
  - Calculate totals, taxes, and discounts

#### 3.5. Deployment & Hosting
- **Host Website**
  - Deploy frontend and backend on Netlify
  - Connect custom domain

- **Testing**
  - Test across devices and browsers
  - Conduct user testing for buying flow, cart, and returns

#### 3.6. Documentation & Final Review
- **Prepare Documentation**
  - Instructions for admin and customer usage
  - Technical documentation for APIs and database structure

#### 3.7. Final QA
- Test end-to-end shopping, checkout, and returns
- Verify performance and responsiveness

*(Additional milestones like "Integration of Dealer Finder" or "Test Ride Booking System" may be added based on sprint progress.)*

---

### 3.8. WBS Structure
<img width="624" height="416" alt="Picture1" src="https://github.com/user-attachments/assets/fd8fa010-13e3-4827-82cd-3aefe8653143" >
<img width="624" height="47" alt="Picture2" src="https://github.com/user-attachments/assets/bcdea38a-f8b4-429a-948e-7808f0e8b9bb" />

### 3.9. Requirements Traceability Matrix
| Req ID | Requirement                             | Del ID | Deliverable                                               | Owner | Status  |
|--------|------------------------------------------|--------|-----------------------------------------------------------|-------|---------|
| REQ01  | Frontend framework selected and set up   | DEL01  | React and CSS implemented for static pages                | Team  | Pending |
| REQ02  | Backend server set up                     | DEL01  | Node.js + Express server running                          | Team  | Pending |
| REQ03  | Database connection established           | DEL01  | MongoDB connected with sample data                        | Team  | Pending |
| REQ04  | Static pages created                      | DEL01  | Home, Product Listing, Product Details pages ready        | Team  | Pending |
| REQ05  | Shopping cart functionality implemented   | DEL02  | Add/remove bikes to cart and calculate totals             | Team  | Pending |
| REQ06  | Product management for admin              | DEL02  | Admin can add/edit/delete bikes and promotions            | Team  | Pending |
| REQ07  | Order management implemented              | DEL02  | Customers can place orders, select pickup/delivery        | Team  | Pending |
| REQ08  | Deployment of website                     | DEL03  | Website hosted on Netlify with a domain                   | Team  | Pending |
| REQ09  | User testing and feedback                 | DEL04  | Testing of buying flow, cart and returns                  | Team  | Pending |


### 4. Deliverables
- Website running from the server with a functional bike catalog.
- Bike catalog with filters and comparison tools.
- Booking system for test rides and maintenance.
- Customer account management.
- Secure checkout with order confirmation and delivery tracking.

### 5. Preliminary Budget 
(to be left empty)

### 6. Organization and Stakeholders
(to be left empty)

### 7. Risks, Assumptions, and Constraints 
(to be left empty)

