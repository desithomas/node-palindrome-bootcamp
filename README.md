# Palindrome Checker


Type in a word or phrase and this app tells you whether it is a palindrome — whether it reads the same forwards and backwards, like "racecar". The check happens on the server, not in your browser: when you submit a word, the browser sends it to Node.js, the server reverses the string and compares it with the original, and your word comes back with a clear yes-or-no answer.


## **Tech Stack:**

* **HTML:** The page and the input form.

* **CSS:** The styling.

* **JavaScript:** The logic in the browser and on the server.

* **Node.js:** A small custom server built with Node's built-in `http` module (which serves the page and receives your entry) and `fs` module (which reads the page files).


<img width="580" height="277" alt="Screenshot 2026-11-09 at 8 03 43 AM" src="https://github.com/user-attachments/assets/e43435b5-5909-436f-b807-efbdfe694abf" />

<img width="547" height="232" alt="Screenshot 2026-11-09 at 8 05 32 AM" src="https://github.com/user-attachments/assets/575ebcb5-6370-4694-a366-4b8ad1f09d99" />

## View on Website: 

https://palindromeorkabob.netlify.app


## **How to Run Locally:**

1. **Clone the repository:**

```bash
git clone https://github.com/desithomas/node-palindrome-bootcamp.git.
cd node-palindrome-bootcamp
```

2. **Install the dependencies:**
```bash
npm install
```

3. **Start the application:**
```bash
node server.js
```

4. **Local Browser View:**
* Go to http://localhost:9000 in your browser

Viola! Racecar (haha) approved. Thank you for using this app!
