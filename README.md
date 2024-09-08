# 🏕️ Explore Camping

**Explore Camping** is a seamless web application that offers users an easy online booking experience to reserve campsites with just a few clicks. It enables users to provide reviews and ratings for campsites, helping others plan their treks more effectively. The app also provides campground owners with effortless management of their campsite listings and associated details. With full CRUD functionality, users can efficiently interact with data. The application utilizes **Cloudinary** for smooth image uploads and **Mapbox** for integrating maps to locate campgrounds. Additionally, the **Passport** node module is employed to implement authentication and authorization functionalities.

---

## 🚀 Features

- **Easy Booking**: Book your favorite campsites quickly and effortlessly through an intuitive interface.
- **Reviews and Ratings**: Share your experiences by providing reviews and ratings for campsites, helping fellow trekkers make informed decisions.
- **Campground Owner Dashboard**: Campground owners can manage their campsite listings and update associated details with ease.
- **CRUD Functionality**: Users can efficiently create, read, update, and delete campground data, providing a seamless data interaction experience.
- **Cloudinary Image Upload**: Easily upload and manage images of campsites using Cloudinary's image storage solution.
- **Map Integration**: Mapbox integration allows users to locate and explore campgrounds on an interactive map.

---

## 🛠️ Technologies Used

- **Cloudinary**: The application utilizes Cloudinary storage for managing image uploads and storage.
- **Mapbox**: Mapbox is integrated to provide users with interactive maps to locate and explore campgrounds.
- **Passport**: The Passport node module is used to implement authentication and authorization functionalities, ensuring secure access to specific features.

---

## 📦 Installation

Follow these steps to set up the Explore Camping web app locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Explore-Camping.git
   cd Explore-Camping
   ```bash


2. **Install the required dependencies**:
     ```bash
     npm install
   
  
3 .**Set up environment variables: Create a .env file in the root directory and add the following**:

    
    PORT=3000
    DATABASE_URL=your_database_connection_string
    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    MAPBOX_ACCESS_TOKEN=your_mapbox_access_token
    SECRET_KEY=your_secret_key_for_jwt
        
       
           
4 .**Run the app**:
    
    npm start



  Open your web browser and navigate to http://localhost:3000 to access Explore Camping.
  
## 📦 Usage

### User Registration/Login
- **Register**: Create a new account to access the full features of Explore Camping.
- **Login**: If you already have an account, log in using your credentials.

### Explore Campgrounds
- **Browse Campgrounds**: View a list of available campgrounds, complete with descriptions, images, and reviews.
- **Integrated Map**: Use the built-in map to explore campground locations and nearby attractions.

### Booking
- **Select a Campground**: Choose a campground from the list that meets your needs.
- **Book**: Easily book the selected campground. You will receive a confirmation email with your booking details.

### Reviews and Ratings
- **Post-Visit Feedback**: After your camping experience, provide a review and rate the campground. Your feedback helps others make informed decisions.

### Campground Owner Dashboard
- **Owner Login**: If you are a campground owner, log in to access your dashboard.
- **Manage Listings**: Update details about your campground, including descriptions, pricing, and availability.
- **View Bookings**: Track all bookings and manage your campground's reservations.

### CRUD Operations
- **Create**: Add new campgrounds or update existing ones.
- **Read**: View details of your campgrounds and bookings.
- **Update**: Modify existing campground details or booking information.
- **Delete**: Remove campgrounds or cancel bookings when necessary.

---

**Happy Camping!** 🏕️
