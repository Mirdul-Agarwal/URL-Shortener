# URL Shortener 🔗  
A simple **URL Shortener** service that takes a valid URL, generates a short URL, and redirects users to the original URL. It also tracks the total number of visits/clicks for each shortened link.  

## Features 🚀  
✅ Generate a shortened URL for any valid link  
✅ Redirect users using the short URL  
✅ Track total visits/clicks for each short URL  

## API Routes 📌  

### 1️⃣ Generate Short URL  
**`POST /url`**  
- Accepts a valid URL in the request body  
- Returns a shortened URL in the format `example.com/random-id`  

### 2️⃣ Redirect to Original URL  
**`GET /:id`**  
- Redirects the user to the original URL associated with the short ID  

### 3️⃣ Get Analytics  
**`GET /url/analytics/:id`**  
- Returns the total number of clicks for the given short ID  

## Tech Stack 🛠  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Short ID Generator:** ShortID  
