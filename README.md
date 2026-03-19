🎵 MUSIFY Login Form (Tkinter with Validation)
📌 Description

This project is a GUI-based login system built using Python’s Tkinter library. It allows users to enter their email and password and provides basic validation using pop-up message boxes.

The application features a clean UI with image integration and user-friendly alerts.

🛠️ Technologies Used

Python 🐍

Tkinter (GUI framework)

Pillow (PIL) for image processing

Tkinter MessageBox for alerts

✨ Features

🎨 Styled login interface with pastel theme

🖼️ Logo/image display

📧 Email input field

🔒 Password input with hidden characters

⚠️ Validation for empty fields

✅ Success and error pop-up messages

📂 Project Structure
project-folder/
│
├── main.py              # Main application file
├── pixel2.ico          # Window icon
├── star.png            # Logo image
└── README.md           # Documentation
▶️ How to Run
1. Install Required Library
pip install pillow
2. Run the Application
python main.py
⚙️ Configuration

Update file paths according to your system:

root.iconbitmap("your_icon_path.ico")
Image.open("your_image_path.png")
🔑 Login Function Logic
def login():
    email = email_entry.get()
    password = password_entry.get()

    if email == "" or password == "":
        messagebox.showwarning("Error", "All fields are required!")
    else:
        messagebox.showinfo("Success", f"Login Successful!\nWelcome {email}")
🧠 Future Enhancements

🔐 Add real authentication (database integration)

📩 Email format validation

👤 Signup/Register page

🗄️ Connect with MySQL / SQLite

🎨 Improve UI using Frames & advanced styling

👁️ Show/Hide password feature
