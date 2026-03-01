# To-Do List Mobile App

A simple and intuitive to-do list application built with React Native and Expo, featuring local storage functionality.

## 📱 Features

- ✅ **Add Tasks** - Create new tasks with ease
- ✅ **Mark Complete** - Check off tasks when completed
- ✅ **Delete Tasks** - Remove tasks you no longer need
- ✅ **Local Storage** - All tasks persist locally on your device
- ✅ **Clean UI** - User-friendly interface with React Native Paper
- ✅ **Cross-Platform** - Works on iOS, Android, and Web
- ✅ **TypeScript** - Type-safe development
- ✅ **State Management** - Zustand for efficient state handling

## 🛠️ Tech Stack

- **Framework**: React Native + Expo
- **Language**: TypeScript
- **State Management**: Zustand
- **UI Library**: React Native Paper
- **Local Storage**: AsyncStorage
- **Navigation**: React Navigation

## 📋 Project Structure

```
Gookye-Company/
├── src/
│   ├── App.tsx
│   ├── screens/
│   │   └── HomeScreen.tsx
│   ├── components/
│   │   ├── TaskItem.tsx
│   │   ├── TaskInput.tsx
│   │   └── EmptyState.tsx
│   ├── stores/
│   │   └── taskStore.ts
│   └── utils/
│       └── storage.ts
├── app.json
├── package.json
├── tsconfig.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Expo CLI

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/gookye-coder/Gookye-Company.git
   cd Gookye-Company
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Run on your device**
   - **iOS**: Press `i` in the terminal
   - **Android**: Press `a` in the terminal
   - **Web**: Press `w` in the terminal
   - **Expo Go**: Scan the QR code with Expo Go app

## 📝 Usage

1. Launch the app
2. Enter a task description in the input field
3. Press "Add Task" button
4. Tap on a task to mark it as complete
5. Swipe or tap the delete button to remove a task

## 🔄 Local Storage

All tasks are automatically saved to your device's local storage using AsyncStorage. Your tasks will persist even after closing and reopening the app.

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:
1. Create a new branch for your feature
2. Commit your changes with clear messages
3. Push to your branch
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**gookye-coder** - [GitHub Profile](https://github.com/gookye-coder)

## 📧 Support

For issues and questions, please create an issue on the GitHub repository.