# Peer-to-Peer Chat App (Gun.js)

A modern, real-time, peer-to-peer chat application built with [Gun.js](https://gun.eco/) and [Tailwind CSS](https://tailwindcss.com/). This project aims to become a full-featured, decentralized chat platform with public and private messaging, user presence, and a beautiful, responsive UI.

## Features

- **Decentralized Messaging:** Uses Gun.js for peer-to-peer, real-time data sync.
- **Public Chat Room:** All users can chat together in a global room.
- **Private Messaging:** Start private conversations with any online user.
- **User Presence:** See who is online in real time.
- **Unique Aliases:** Choose or generate a unique name to join the chat.
- **Modern UI:** Responsive, dark-themed interface powered by Tailwind CSS.
- **No Backend Required:** Runs entirely in the browser using distributed Gun.js peers.

## Demo

> _Coming soon!_

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari, etc.)
- Internet connection (for Gun.js relay and CDN assets)

### Running Locally
1. **Clone or Download the Repository:**
   ```sh
   git clone https://github.com/yourusername/peertopeer-chat.git
   cd peertopeer-chat
   ```
2. **Open `index.html` in your browser:**
   - Double-click `index.html` or open it with your preferred browser.
   - _No build step or server required!_

### Folder Structure
```
peertopeer-chat/
├── index.html        # Main application (HTML, CSS, JS)
├── README.md         # Project documentation
```

## Usage
1. On load, the app connects to the Gun.js peer network.
2. Enter a unique name or generate a cool alias to join.
3. Chat in the public room or click a user to start a private chat.
4. Your presence and messages sync in real time with all connected peers.

## Tech Stack
- **Frontend:** HTML, Tailwind CSS, Vanilla JavaScript
- **P2P Database:** [Gun.js](https://gun.eco/) (with SEA for security)

## Roadmap / Future Plans
This project is in early development. Planned features include:
- [ ] **User Authentication:** Persistent logins, password reset, etc.
- [ ] **Message Encryption:** End-to-end encryption for private chats.
- [ ] **Media Sharing:** Images, files, and more.
- [ ] **Notifications:** Desktop and in-app notifications.
- [ ] **Group Chats:** Create and join group/private rooms.
- [ ] **Profile Avatars:** Custom user images.
- [ ] **Message Reactions:** Emojis, likes, etc.
- [ ] **Mobile PWA Support:** Installable, offline-capable app.
- [ ] **Moderation Tools:** Reporting, blocking, and admin controls.
- [ ] **Theming:** Light/dark mode, custom themes.

## Contributing
Contributions, bug reports, and feature requests are welcome! Please open an issue or submit a pull request.

## License
[MIT](LICENSE)

## Acknowledgments
- [Gun.js](https://gun.eco/) for decentralized data sync
- [Tailwind CSS](https://tailwindcss.com/) for rapid UI development
- [Feather Icons](https://feathericons.com/) for beautiful icons 