# Mission 7: How Computers Communicate

## 1. Task / objective

To explain basic network types and concepts, observe network connectivity and DNS information, and describe what happens when a website opens.

## 2. Work completed

I explained eight network concepts, tested connectivity and did a DNS lookup for `example.com`, and wrote a seven-step explanation of how a website opens.

### Task 7.1: Explain Network Concepts

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

### Task 7.2: Observe Network Information

| Command | What I observed (privacy-safe) |
|---|---|
| `ping -c 4 example.com` | I received all 4 replies, and there was 0% packet loss. |
| `nslookup example.com` | It showed two public IP addresses for `example.com`: `172.66.147.243` and `104.20.23.154`. |

- **Connectivity test:** It checks whether my computer can connect to another computer and how quickly it responds.
- **DNS lookup:** It shows the IP addresses connected to a website name.
- **Role of DNS:** When I type a website name in my browser, DNS finds its IP address. The browser uses that IP address to connect to the website.

### Task 7.3: What Happens When You Open a Website?

1. First, I type a website name into my browser. The browser acts as a **client** because it asks for the website.
2. The browser asks **DNS** to find the IP address of the website name.
3. DNS finds the IP address and sends it back to the browser.
4. My request leaves my computer, passes through my router and travels across the internet in small pieces called packets.
5. The website's **server** receives my request. The browser and server communicate using a **protocol** like HTTP or HTTPS.
6. The server sends the requested webpage back to my computer.
7. Finally, my browser receives the page and displays it on the screen.

## 3. Commands / tools used

- `ping -c 4 example.com` – Sends 4 test messages to a website to check that my computer can reach it.
- `nslookup example.com` – Asks DNS for the IP address linked to a website name.
- `git status`, `git add`, `git commit`, `git push` – Used to check, stage, save and upload my work.
- VS Code – Used to write and edit the README file.

## 4. My understanding

I learned how computers connect and communicate with each other through networks. I understood the difference between LAN, MAN and WAN, and how routers and protocols help computers communicate. I also learned that DNS finds the IP address for a website name, and that data travels across a network as small packets.

## 5. Difficulties faced

Initially, I found it difficult to understand how DNS, IP addresses and routers work together when opening a website.

## 6. How I resolved them

I wrote the website steps in order, from the browser asking DNS to the server sending the page back, which showed me where each part fits.

## 7. Evidence / files

- `mission-07-networking/README.md`
- No personal network details are included. Only the public `example.com` addresses are shown.

## 8. Commit details

- Commit message: `Explain networking concepts and website communication`
- Status: Pushed to GitHub.