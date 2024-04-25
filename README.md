# button-code
button
import tkinter as tk

# Function to execute when the button is clicked
def button_click():
    print("Button clicked!")

# Create the main application window
root = tk.Tk()
root.title("Button Example")

# Create a button widget
button = tk.Button(root, text="Click Me!", command=button_click)
button.pack(pady=10, padx=20)  # Add some padding around the button

# Start the Tkinter event loop
root.mainloop()
