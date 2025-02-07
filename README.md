# Job Search Mobile App

A React Native mobile application built with Expo and TypeScript that helps users find and apply to design jobs. The app features a clean, modern UI with job listings, detailed job views, and quick application functionality.

## Features

- Job search and filtering functionality
- Detailed job descriptions with company information
- Salary information display
- Job recommendations based on user profile
- Quick apply functionality
- Job bookmarking
- Recent job listings view
- User profile management

## Tech Stack

- React Native
- Expo
- TypeScript
- React Navigation
- Expo Vector Icons

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Expo CLI
- iOS Simulator (Mac only) or Android Studio (for Android emulator)

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd job-search-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npx expo start
```

## Key Components

### HomeScreen
- Displays user greeting
- Shows job recommendations
- Lists recent job postings
- Includes search functionality

### JobDetailScreen
- Presents detailed job information
- Company details
- Job responsibilities
- Required skills
- Apply now button
- Salary information

## Styling

The app uses a consistent color scheme:
- Primary Blue: `#4A69FF`
- Background: `#FFFFFF`
- Text Primary: `#000000`
- Text Secondary: `#666666`

## Running Tests

```bash
npm test
# or
yarn test
```

## Building for Production

1. For Android:
```bash
eas build -p android
```

2. For iOS:
```bash
eas build -p ios
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Contact

Your Name - [your-email@example.com](mailto:your-email@example.com)
Project Link: [https://github.com/yourusername/job-search-app](https://github.com/yourusername/job-search-app)