# Palindrome Checker
A web app that checks whether a word is a palindrome (spelled the same forwards and backwards). The check runs on a Node.js server built with only Node's core modules, no Express.

## Preview
<img width="1874" height="363" alt="Screenshot 2026-11-23 at 4 39 05 PM" src="https://github.com/user-attachments/assets/e43d7940-7f42-460b-ae41-4d83bc19f122" />

## Live Demo
[Try out the Palindrome Checker!](https://palindrome-backend-x6rz.onrender.com/)


## Features
- Enter a word and get an instant result
- Case-insensitive check (Racecar counts as a palindrome)
- Server returns JSON from a simple API endpoint

## Tech Stack
- HTML 
- CSS
- JavaScript
- Node.js

## How It Works
- The browser sends the word to `GET /api?palindrome=<word>` 
- The server lowercases it, reverses it, compares the two and responds:

```
{ "palindrome": true
}
```
Run Locally
Requires Node.js. No dependencies to install.

1. Cline the repository:
```bash
git clone https://github.com/CarlyJovon/palindrome-backend.git
```
2. Navigate to the project directory:
```
cd palindrome-backend
```
3. Start the server
```bash 
node server.js
```

5. Open `http://localhost:3000`
