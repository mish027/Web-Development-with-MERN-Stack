# 🌐 How the Internet Works

If a client is requesting for a particular webpage that request will go all the way round to the server via internet. In response to that request, the server will respond with that particular page that the client has requested for.

## 🔄 Step-by-Step Flow

1. Client: You type "www.google.com" in your browser and the browser prepares a request for that page.

2. ISP (Internet Service Provider):Your request first goes to your ISP, which gives you access to the internet.

3. DNS (Domain Name System): DNS converts the website name ("www.google.com") into an IP address (like 142.250.190.78).This is necessary because computers understand IP addresses, not names.

4. Server (Web Server):The request is sent to the server that hosts the website.The server processes the request and sends back the webpage data (HTML, CSS, JavaScript).

5. Response to Client:The data travels back through the internet → ISP → your browser.The browser interprets the code and displays the website.

Client (Browser)
   ↓
ISP (Internet Provider)
   ↓
DNS (Finds IP address of website)
   ↓
Server (Hosts the website)
   ↓
Client (Browser displays the page)

### for example
- You type google.com in Chrome and press Enter.
Browser → DNS → ISP → Google’s Server → Response.
Google’s homepage loads. ✅

- In the Google search bar, you type “cats” and hit Enter.
Again, your browser sends a new request to Google’s server, now asking for search results for “cats.”
Google’s server processes the query and sends back a results page (lots of links, images, etc.).
You now see the search results. ✅


- Click on Wikipedia link
You see a result: “Cats – Wikipedia.”
You click it.
Your browser now leaves Google’s server and talks to Wikipedia’s server.
Again, DNS → ISP → Wikipedia server → Response.
Wikipedia’s page loads. ✅


- Click another link (e.g., YouTube)
From the results, you now click YouTube.
This time, your browser starts talking to YouTube’s server.
DNS → ISP → YouTube server → Response.
YouTube opens. ✅

⚡ Analogy:
Imagine visiting a mall (Google).
First, you enter the mall → that’s the homepage.
Then you ask the info desk where “cat-related stores” are → that’s the search.
The info desk gives you a list of shops → search results.
Now, if you actually walk into one shop (Wikipedia), you leave the info desk and interact with the shop directly.
If you go to another shop (YouTube), that’s another new interaction.