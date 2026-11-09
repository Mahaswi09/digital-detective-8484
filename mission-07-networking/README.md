# Mission 7 - How computers communicate

## Task 7.1 - Explain network concepts
| Concept | Explain it in your own words | Example |
|---|---|---|
| LAN | A network that connects computers in a small area. | Computers connected in a college lab. |
| MAN | A network that connects computers across a city. | A network connecting different branches of a college in one city. |
| WAN | A network that connects computers over large distances. | The Internet. |
| DNS | It converts website names into IP addresses so computers can find them. | Converting `google.com` into an IP address. |
| Router | A device that connects networks and sends data to the correct place. | A Wi-Fi router at home. |
| Protocol | A set of rules that computers follow to communicate with each other. | HTTP and HTTPS. |
| Packet switching | Data is broken into small pieces called packets and sent across a network. | Sending a photo over the Internet. |
| Client-server | A system where one computer requests something and another computer provides it. | A web browser requesting a webpage from a web server. |

## Task 7.2 - observe network information
### Commands Used

- `ping -c 4 example.com`
- `nslookup example.com`

- **Connectivity test:** It checks whether my computer can connect to another computer and how quickly it responds. I received all 4 replies, and there was 0% packet loss.

- **DNS lookup:** It shows the IP addresses connected to a website name. For `example.com`, I got `172.66.147.243` and `104.20.23.154`.

- **Role of DNS:** When I type a website name in my browser, DNS finds its IP address. The browser uses that IP address to connect to the website.

## Task 7.3 - What happens when you open a website?

1. First, I type a website name into my browser. The browser acts as a **client** because it asks for the website.
2. The browser asks **DNS** to find the IP address of the website name.
3. DNS finds the IP address and sends it back to the browser.
4. My request leaves my computer, passes through my router and travels across the internet in small pieces called packets.
5. The website's **server** receives my request. The browser and server communicate using a **protocol** like HTTP or HTTPS.
6. The server sends the requested webpage back to my computer.
7. Finally, my browser receives the page and displays it on the screen.

## What I Understood

I learned how computers connect and communicate with each other through networks. I understood the difference between LAN, MAN and WAN. I learned how routers and protocols help computers communicate.

## Difficulty Faced

Initially, I found it difficult to understand how DNS, IP addresses and routers work together when opening a website.
