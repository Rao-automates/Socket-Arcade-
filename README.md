# Socket Arcade 🎮

![Socket Arcade Banner](assets/banner.png)

**Socket Arcade** is a real-time multiplayer game server built with Flask and Socket.IO. It transforms your local network into a gaming party hub, allowing devices to connect seamlessly via Wi-Fi and play classic arcade games together.

## 🚀 Features

-   **Zero-Setup Multiplayer**: hosted on your local network (LAN).
-   **Real-time Interaction**: Powered by WebSockets for instant feedback.
-   **Cross-Device Support**: Play on mobile, tablet, or desktop.
-   **Secure Connection**: Built-in HTTPS support (Self-signed or Adhoc).

## 🕹️ Game Library

| Tic-Tac-Toe | Racing |
|:---:|:---:|
| ![Tic Tac Toe](assets/tictactoe.png) <br> **Neon Tic-Tac-Toe** <br> <sub>Classic strategy with a cyberpunk twist.</sub> | ![Racing](assets/racing.png) <br> **Tap Racing** <br> <sub>Mash buttons to race your car to the finish line!</sub> |

### Other Games Included:
*   **Number Guessing**: Test your intuition against a friend.
*   **Rock Paper Scissors**: The ultimate decision maker.
*   **Reaction Test**: Who has the fastest reflexes?
*   **Click War**: A chaotic battle of speed.

## 🛠️ Installation & Usage

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/socket-arcade.git
    cd socket-arcade
    ```

2.  **Install Dependencies**:
    ```bash
    pip install flask flask-socketio eventlet
    ```

3.  **Run the Server**:
    ```bash
    python server.py
    ```

4.  **Connect**:
    *   The console will display your LAN IP address (e.g., `https://192.168.1.X:5000`).
    *   Open this URL on any device connected to the same Wi-Fi.
    *   *Note: Accept the security warning (since it uses a self-signed certificate).*

## 🤝 Contributing

Pull requests are welcome! Feel free to add new games or improve the UI.

## 📄 License

MIT
