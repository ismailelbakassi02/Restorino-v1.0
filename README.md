# Restorino

**Restorino** is a modern, interactive restaurant review web app built with Flask. It features a unique menu book experience, food challenges, and robust role-based access for admins, restaurant owners, and tourists.

## Features

- **Interactive Menu Book**: Browse restaurant menus as a beautiful, animated book. Menu images and items are displayed with page-flip effects, zoom, and admin/owner controls.
- **Menu Item & Image Management**: Owners and admins can add, edit, and delete menu items and menu images directly from the menu book or modal.
- **Food Challenges**: Tourists can participate in culinary challenges, earn badges, and share experiences.
- **Role-Based Access**:
  - **Admins**: Manage all restaurants, menu items, images, and users. Super user privileges.
  - **Restaurant Owners**: Manage their own restaurant(s), menus, and images.
  - **Tourists**: Discover, review, and participate in food challenges.
- **Profile Management**: Customizable profiles for all users.
- **Responsive UI**: Clean, modern, and mobile-friendly design.

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd restorino V Final
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the database**
   - The app uses SQLite by default. The database will be created automatically on first run.
   - To create an initial admin user, see `app.py` (default: admin@restorino.com / admin123).

5. **Run the app**
   ```bash
   flask run
   ```
   Or use the provided `run.py`:
   ```bash
   python run.py
   ```

6. **Access the app**
   - Open [http://localhost:5000](http://localhost:5000) in your browser.

## Usage

- **Admins**: Log in with the admin account to access all management features.
- **Owners**: Register as a restaurant owner to add and manage your restaurant and menu.
- **Tourists**: Register as a tourist to explore, review, and join food challenges.

## Contribution

Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch for your feature or fix
3. Submit a pull request with a clear description

## Team

- **Head Developer:** Aboulhassan Rayan
- **Team:** Zaynab El AIADI, Selya Bathahi, Yasmine Mouhib, Adnan El Aiadi, Adam Villar, Adam Skouri, Ibrahim El Mansouri, Yahya Alloucha

## License

This project is licensed under the MIT License.

---

**Restorino** – Bringing Agadir's culinary scene to your fingertips!
