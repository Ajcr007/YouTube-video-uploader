# YouTube Video Uploader (Core PHP)

## Description
This is a simple project built with Core PHP that connects to YouTube using Google's API to upload videos to a YouTube channel. The project uses a hardcoded PHP API to handle authentication and video uploads.

## Features
- Upload videos to a YouTube channel via Google API.
- Uses **Client ID**, **Secret Key**, and **API Key** from Google Cloud.
- Simple **index.php** file for handling uploads.

## Repository Information
**Repository Name:** `youtube-video-uploader`

## Installation & Setup

### Prerequisites
- PHP 8.0 or later
- A Google Cloud project with YouTube Data API enabled
- Google OAuth 2.0 credentials (Client ID, Secret Key, and API Key)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/youtube-video-uploader.git
   cd youtube-video-uploader
   ```

2. Create a Google Cloud project and enable **YouTube Data API v3**:
   - Go to [Google Cloud Console](https://console.cloud.google.com/)
   - Create a new project
   - Enable "YouTube Data API v3"

3. Generate API Credentials:
   - Create OAuth 2.0 Client ID
   - Generate API Key
   - Download the **client_secret.json** file

4. Place your **Client ID**, **Secret Key**, and **API Key** inside `index.php`:
   ```php
   $client_id = 'YOUR_CLIENT_ID';
   $client_secret = 'YOUR_CLIENT_SECRET';
   $api_key = 'YOUR_API_KEY';
   ```

5. Start a PHP server:
   ```bash
   php -S localhost:8000
   ```

6. Open your browser and visit:
   ```
   http://localhost:8000/index.php
   ```

## Technologies Used
- **Core PHP**
- **Google YouTube Data API v3**
- **OAuth 2.0 Authentication**

## References
- [Google YouTube API Documentation](https://developers.google.com/youtube/registering_an_application)

## License
[MIT](LICENSE)

