## 📌 What are Cookies?

**Cookies** are small pieces of data stored by the **browser** that help a website **remember information about a user** across multiple HTTP requests.

In simple words:  
Cookies are a **memory mechanism for the web** that allows websites to recognize users and maintain state.

Cookies are commonly used for **session management, authentication, and user preferences** in web applications.

---

## 🌐 Before Cookies Were Invented

Before cookies existed, websites communicated using **HTTP requests**.

HTTP (and later HTTPS) is **stateless**, meaning:
- Each request is independent
- The server does not remember previous requests
- Every request looks like it comes from a new user

Because of this:
- Users could not stay logged in
- There were no shopping carts
- No personalization or user sessions

Even with **HTTPS**, which secures communication, the problem remained:
> HTTPS secures data in transit, but it does not remember users.

---

## 🍪 Why Cookies Were Introduced

Cookies were invented to solve this problem of **stateless HTTP**.

They allow:
- The browser to store small pieces of data
- The browser to automatically send that data with every request
- The server to recognize returning users

This enabled:
- Login sessions
- Persistent authentication
- Personalized web experiences

---

## 🔄 How Cookies Work (Simple Flow)

1. User visits a website  
2. Server sends a response with a `Set-Cookie` header  
3. Browser stores the cookie  
4. Browser automatically sends the cookie with future requests  
5. Server recognizes the user

---