# YouTube Downloader Backend

This is a simple Node.js backend API that extracts direct video download URLs from a given YouTube link.

## API Endpoint

- **POST** `/getVideoLinks`  
  Body (application/x-www-form-urlencoded):
  - `youtubeUrl`: The full YouTube URL

### Example Request

```bash
curl -X POST https://your-backend-url.com/getVideoLinks \
  -d youtubeUrl="https://www.youtube.com/watch?v=zsix_Z_9Zk4"