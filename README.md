 How the Chatbot Works:

1. While Loop: We use a `while True` loop to keep the chatbot running continuously. The loop keeps asking for user input until the user types an exit command like "bye", "exit", or "quit".

2. User Input: We take input from the user using the `input()` function and convert it to lowercase using `.lower()` to make matching easier (so "HELLO", "Hello", "hello" all work the same).

3. If-Else Logic: We use if-else statements to check what the user said:
   - If the user says "hello", "hi", or "hey" → Bot greets them
   - If the user says "how are you" → Bot responds about itself
   - If the user says "what is your name" → Bot tells its name
   - If the user says "help" → Bot shows available commands
   - If the user says "bye", "exit", or "quit" → Bot exits and breaks the loop

4. Default Response: If the user types something the bot doesn't recognize, it gives a default message asking the user to try the "help" command.

5. Break Statement: When the user exits, the `break` statement stops the while loop and ends the program.

Key Concepts Used:
- Control Flow (while loop, if-else statements)
- String matching and comparison
- Decision-making logic
- Continuous execution until exit condition
