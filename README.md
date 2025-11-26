# chatbot
🎯 Objective

Create a chatbot that responds to user messages using predefined rules.

🛠 Tools Used

Python

📂 Features

Responds to greetings

Answers simple questions

Uses keyword matching

Runs in a loop until the user types “exit”

Perfect for learning chatbot logic

📁 Project Structure
RuleBasedChatbot/
│── chatbot.py        # Main script
└── README.md

🔧 How It Works

The program runs an infinite loop

It reads user input using input()

if-elif-else statements determine the correct response

When the user types "exit" or "bye", the chatbot stops

▶️ How to Run

Run the chatbot from your terminal:

python chatbot.py

🧠 Example Script (chatbot.py)
print("Chatbot: Hello! Type 'exit' to end the chat.")

while True:
    user = input("You: ").lower()

    if user in ["hi", "hello", "hey"]:
        print("Chatbot: Hello! How can I help you?")
    elif "how are you" in user:
        print("Chatbot: I'm doing great! Thanks for asking.")
    elif "name" in user:
        print("Chatbot: I'm a simple rule-based chatbot created in Python.")
    elif user in ["bye", "exit"]:
        print("Chatbot: Goodbye! Have a nice day!")
        break
    else:
        print("Chatbot: I'm not sure how to respond to that.")

✅ Outcome

By completing this project, you will:

✔ Learn basic chatbot flow
✔ Understand input/output loops
✔ Use conditional statements effectively
✔ Build a foundation for more advanced chatbot systems
