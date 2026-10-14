## Part 2 - Sending messages

After a successful login the app shows:
Welcome to QuickChat.

Menu:
1) Send Messages
2) Show recently sent messages
3) Quit

Option 2 displays: Coming Soon.

Send Messages:
- User enters how many messages to send.
- Each message gets a random 10-digit Message ID.
- Recipient must start with +27, example +27718693002.
- Message text must be 250 characters or less.
- A Message Hash is created from the first two digits of the ID, the message number, and the first and last words in CAPS.
  Example: 00:0:HITONIGHT

After the message is captured the user chooses:
1) Send Message
   Message successfully sent.
2) Disregard Message
   Press 0 to delete the message.
3) Store Message to send later
   Message successfully stored.
   Stored messages are written to stored_messages.json

After a sent message the app displays:
Message ID, Message Hash, Recipient, Message

At the end it displays the total number of messages sent.

Part 2 demo:
- Recipient: +27718693002
- Message: Hi Mike, can you join us for dinner tonight?
- Invalid recipient: 08575975889

Classes:
- Message
- MessageTest

Git branch: KhanbanTasks

---
