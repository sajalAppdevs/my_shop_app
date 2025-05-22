# My Shop - Flutter E-commerce App

A feature-rich Flutter e-commerce application with Firebase backend integration, offering a seamless shopping experience with user authentication, product management, and secure payment processing.

## Features

### User Authentication
- Secure user registration and login system
- Persistent user sessions using shared preferences
- Password reset functionality

### Product Management
- Browse through a diverse catalog of products
- View detailed product information and images
- Add products to favorites for quick access
- Search and filter products by categories
- Manage your own products (add, edit, delete)

### Shopping Experience
- Intuitive shopping cart functionality
- Real-time price calculations
- Order history tracking
- Secure payment processing

### Admin Features
- Product inventory management
- Add new products with images and descriptions
- Edit existing product details
- Remove products from the catalog

## Tech Stack

- **Frontend:** Flutter SDK
- **State Management:** Provider
- **Backend:** Firebase
- **Authentication:** Firebase Auth
- **Database:** Firebase Realtime Database
- **Storage:** Firebase Storage (for product images)

## Dependencies

- `provider`: For state management
- `http`: For API communication
- `intl`: For date formatting
- `firebase_core`: Firebase core functionality
- `firebase_auth`: For user authentication

## Getting Started

### Prerequisites

- Flutter SDK (latest version)
- Android Studio/VS Code with Flutter plugins
- Firebase account and project setup

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/my_shop_app.git
```

2. Install dependencies
```bash
flutter pub get
```

3. Configure Firebase
   - Create a new Firebase project
   - Add Android/iOS apps in Firebase console
   - Download and add the configuration files
   - Enable Authentication and Realtime Database

4. Run the app
```bash
flutter run
```

## App Screenshots

### Product Overview and Authentication
<img src="https://user-images.githubusercontent.com/92157668/192320803-92f0645a-c3c5-4edd-a171-f0ac6a994a3d.jpg" width="300" height="600"> <img src="https://user-images.githubusercontent.com/92157668/192320928-3f67c397-9be9-4360-94db-09b4efc36d18.jpg" width="300" height="600">

### Shopping Cart and Product Management
<img src="https://user-images.githubusercontent.com/92157668/192321238-30bde989-7bb8-4fcb-90cb-bd611be13bb8.jpg" width="300" height="600"><img src="https://user-images.githubusercontent.com/92157668/192321131-f87fe2d6-31ea-40c5-903d-f804116e9dec.jpg" width="300" height="600">

### Order History
<img src="https://user-images.githubusercontent.com/92157668/192321347-3f716f81-2713-4da1-a18d-07b7da449fc2.jpg" width="300" height="600">

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

