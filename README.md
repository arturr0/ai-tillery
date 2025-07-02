## Neural Network Ballistics  
[![Status](https://img.shields.io/badge/status-prototype-blueviolet)](https://ai-tanks.onrender.com)  
![Tech](https://img.shields.io/badge/-Node.js-339933) ![Tech](https://img.shields.io/badge/-Socket.io-010101) ![Tech](https://img.shields.io/badge/-p5.js-ED225D)  

🖼️ **Preview**:  
![Game Preview](https://cdn.glitch.global/79283f6f-ef1e-4285-822b-eaefe68c462e/t.png)

🌐 **Live Demo**: [https://ai-tanks.onrender.com](https://ai-tanks.onrender.com)  

*A real-time multiplayer tank battle game where players train neural networks to aim and fire projectiles.*  

⚠️ **Important Note**: Requires 2 active players. When testing locally, keep both browser tabs visible for synchronized training.  

### ✨ Features  

#### Core Gameplay  
- Real-time tank combat physics  
- Dynamic wind simulation  
- Destructible tank models with particles  
- Neural network aiming system  

#### Neural Network  
- 3-layer architecture (1 input, 2 hidden, 1 output)  
- Real-time training visualization  
- Adaptive learning with momentum  
- Loss function tracking  

#### Multiplayer  
- WebSocket-based real-time sync  
- Low-latency projectile physics  
- Shared game state management  
- 2-player battle system  

### 🤖 Model vs Model Battles  
- **Live Training Duel**: Players simultaneously train their models during combat  

### 🛠️ Technical Stack  
| Component       | Technology                          |
|-----------------|-------------------------------------|
| Backend        | Node.js Express |
| Realtime       | Socket.io |
| Physics        | Matter.js |
| Graphics       | ![p5.js](https://img.shields.io/badge/-p5.js-ED225D) |
| Visualization  | Chart.js |
