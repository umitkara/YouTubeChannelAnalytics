# YouTube Channel Analytics

A small simple web app that provides analytics for YouTube channels. For an end-user sometimes I want to watch popular but recent videos, but YouTube does not provide a way to filter videos by popularity within a specific time range. This app allows users to analyze YouTube channels by entering their handle or URL, selecting a time range, and viewing detailed statistics about the channel's most popular videos.

Provide a channel URL like https://www.youtube.com/@Youtube and an API key.

## Technologies Used

- **React**: For building the user interface.
- **Recharts**: For creating interactive charts.
- **Tailwind CSS**: For styling the application.
- **YouTube Data API v3**: For fetching channel and video data.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Open the `index.html` file in your browser to run the application.

## Usage

1. Enter the YouTube channel handle or URL in the input field.
2. Select a time range or set a custom date range.
3. Provide your YouTube API key.
4. Click the "Analyze" button to fetch and display analytics.

## Notes

- Ensure you have a valid YouTube Data API key to use this application.
- The application limits the number of videos fetched to 500 to avoid excessive API usage.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
