# Trust Bank

Welcome to Trust Bank, a project designed to provide a seamless online banking experience. Developed using Django, Trust Bank allows users to manage their finances with ease. Key features include user registration and login, deposit and withdrawal transactions, and transaction history tracking.

## Features

- **User Registration**: Create a new user account with secure email authentication.
- **User Login**: Secure login process for authenticated users.
- **Deposit Amount**: Deposit funds into your account.
- **Withdraw Amount**: Withdraw funds from your account.
- **Transaction History**: View and track all your past transactions.

## Technologies Used

- **Python**
- **Django**
- **SQLite**
- **HTML**
- **CSS**
- **JavaScript**
- **Bootstrap**

## Getting Started

### Prerequisites

- Python 3.x
- Django 3.x or higher
- SQLite

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Thamaraiselvan16/Trust_Bank
    cd Trust_Bank
    ```

2. **Create a virtual environment and activate it:**
    ```sh
    pip install virtualenv
    python -m venv venv_name
    source venv_name/Scripts/activate  # On macOS/Linux, use `source venv_name/bin/activate`
    ```

3. **Install the required packages:**
    ```sh
    cd django_banking
    pip install -r requirements.txt
    ```

4. **Run migrations:**
    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

5. **Start the development server:**
    ```sh
    python manage.py runserver
    ```

### Usage

1. **Register an Account**: Create a new user account with email authentication.
2. **Login**: Log in with your verified account.
3. **Deposit Funds**: Add money to your account through the deposit feature.
4. **Withdraw Funds**: Withdraw money from your account.
5. **View Transaction History**: Access and review your transaction history.

## Acknowledgments

- Thanks to the open-source community for their tools and resources.
- Special thanks to the Django community for their excellent tools and documentation.

---

We hope you enjoy using Trust Bank. If you have any questions or feedback, feel free to open an issue or contact us.
