# YouTube Comment Analyzer Chrome Extension

This project is a Chrome extension that analyzes comments on a YouTube video and shows sentiment insights. It helps viewers understand whether comments are mostly positive, negative, or neutral by fetching comments from the video, sending them to a backend service for sentiment analysis, and displaying summary results in the extension popup.

The extension can show:
- total number of comments
- unique commenters
- average comment length
- average sentiment score
- sentiment distribution chart
- sentiment trend graph
- word cloud
- AI summary of the comments
- top comments with sentiment labels

## How to add the extension in Chrome

1. Open Google Chrome.
2. Go to `chrome://extensions`.
3. Turn on Developer mode in the top-right corner.
4. Click the Load unpacked button.
5. Select the project folder containing this extension files.
6. The extension will appear in your Chrome toolbar.

## How to use it

1. Open any YouTube video in Chrome.
2. Click the extension icon in the Chrome toolbar.
3. The popup will read the current video URL and fetch the comments.
4. Wait while the extension analyzes the comments and loads the results.
5. View the summary, sentiment graph, word cloud, and comment insights.

## Backend project

This extension works with the backend service for sentiment analysis and chart generation.

Backend repository: https://github.com/15y-pankaj/yt-comment-sentiment-analysis

## Notes

- The extension depends on a backend API for sentiment analysis and chart generation.
- Make sure the backend service is running and reachable before using the extension.
- If you are testing locally, you may need to update the API URL in the extension code if the backend address changes.
- For setup details and API endpoints, follow the instructions in the backend project repository linked above.

## Project files

- `manifest.json` — Chrome extension configuration
- `popup.html` — popup UI layout
- `popup.js` — logic to fetch comments and display analysis
