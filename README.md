# YouTube Channel Analytics

A simple web app that provides analytics for YouTube channels. YouTube doesn't provide an easy way to filter videos by popularity within a specific time range. This app solves that problem by allowing you to analyze channels, view detailed statistics, and organize videos into collections.

## Features

- **Time-Based Analysis**: Fetch videos from any time range (last 24 hours to 5 years, or custom date range)
- **Advanced Filtering**: Filter videos by duration, type, view count, and search titles (client-side, no additional API calls)
- **Visual Analytics**: Interactive bar charts showing the most popular videos
- **Collections**: Organize videos into custom collections stored locally using IndexedDB
- **Bulk Operations**: Select multiple videos and add them to collections at once
- **Detailed Video Information**: View thumbnails, duration, views, publish date, and video type for each video

## Screenshots

### All Videos Tab
![All Videos Tab](screenshot-all-videos.png)

### Collection View
![Collection with Videos](screenshot-collection.png)

## Technologies Used

- **React**: For building the user interface
- **Recharts**: For creating interactive charts
- **Tailwind CSS**: For styling the application
- **YouTube Data API v3**: For fetching channel and video data
- **IndexedDB**: For storing collections locally

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Open the `index.html` file in your browser to run the application.

3. Get a YouTube Data API v3 key from the [Google Cloud Console](https://console.cloud.google.com/apis/credentials)

## Usage

1. Enter a YouTube channel handle (e.g., `@Youtube`) or URL in the input field
2. Select a time range or set a custom date range
3. Enter your YouTube API key
4. Click **Analyze** to fetch and display video analytics
5. Use filters to narrow down results by duration, type, views, or title
6. Create collections to organize videos
7. Select videos and add them to collections for later reference

## Collections Feature

- **Create Collections**: Organize videos into custom-named collections
- **Rename/Delete**: Manage your collections with easy rename and delete options
- **Persistent Storage**: Collections are saved locally in your browser using IndexedDB
- **Quick Add**: Add individual videos or select multiple videos for bulk operations
- **Collection Filtering**: All filters work within collections too

## Notes

- A valid YouTube Data API key is required to use this application
- The application limits fetches to 500 videos to avoid excessive API usage
- All video filtering is done client-side after the initial fetch
- Collections are stored locally in your browser and won't be lost on refresh

## License

This project is licensed under the MIT License. See the LICENSE file for details.
