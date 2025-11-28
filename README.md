# nestjs-realtime-chat

A scalable real-time chat application that enables peer-to-peer messaging and group conversations. Built with NestJS for server-side logic, MongoDB for data storage, and WebSockets for instant bidirectional communication.

**Features**
- User authentication with Passport and JWT
- Real-time peer-to-peer messaging
- Room-based group conversations
- WebSocket integration for low-latency communication
- MongoDB with Mongoose for data modeling
- Command-line seeding for initial data

**Technology Stack**
- **NestJS** - Progressive Node.js framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **WebSockets** - Real-time bidirectional communication
- **Socket.IO** - Real-time web application library
- **Passport** - Authentication middleware
- **JWT** - JSON Web Tokens for secure authentication

**Project Structure**
```
src/                - Application source code
test/               - Test files
.env.example        - Environment variables template
```

**Installation**
```bash
npm install
```

**Running the Application**

Development mode:
```bash
npm run start
```

Watch mode (auto-restart on changes):
```bash
npm run start:dev
```

Production mode:
```bash
npm run start:prod
```

**Key Functionality**
- Secure user registration and login
- Real-time message delivery
- Chat room creation and participation
- Paginated chat history
- WebSocket-based live updates

**Recent Updates**
- Implemented pagination for chat room messages
- Enhanced JWT authentication with Passport
- Improved WebSocket chat implementation

**Contributing**
Contributions are welcome. Feel free to open issues for bug reports, feature suggestions, or submit pull requests for improvements.
