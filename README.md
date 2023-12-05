# data_module.py

class UserData:
    def __init__(self, username, email, age):
        self.username = username
        self.email = email
        self.age = age

    def display_user_info(self):
        print(f"Username: {self.username}")
        print(f"Email: {self.email}")
        print(f"Age: {self.age}")

# Example usage:
if __name__ == "__main__":
    # Creating an instance of UserData
    user1 = UserData(username="john_doe", email="john@example.com", age=25)

    # Accessing and modifying data
    user1.age = 26

    # Displaying user information
    user1.display_user_info()
