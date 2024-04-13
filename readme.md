# Reddit to Instagram Meme Poster

This Python script automates the process of fetching top memes from a Reddit subreddit and posting them to Instagram.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- `pip` package manager
- Required Python packages: `praw`, `instagrapi`, `dotenv`

## Setup

1. Clone this repository or download the script.
2. Install dependencies by running `pip install praw instagrapi python-dotenv`.
3. Create accounts and obtain API credentials for Reddit.
4. Create a `.env` file in the same directory as the script and add your credentials in the following format:
    ```dotenv
    CLIENT_ID=your_reddit_client_id
    CLIENT_SECRET=your_reddit_client_secret
    PASSWORD=your_reddit_password
    USER_AGENT=your_reddit_user_agent
    USERNAME=your_reddit_username
    ```
5. Modify the hashtags variable to include the desired hashtags for your Instagram posts.

## Usage

1. Run the script by executing `python bot.py`.
2. Enter your Instagram username and password when prompted.
3. The script will fetch top memes from the specified Reddit subreddit (`r/meirl` by default), download them, and post them to your Instagram account.
4. Memes will be posted with the specified hashtags.
5. The script runs indefinitely, posting a new meme every 3 hours.

## Disclaimer

**Use at your own risk**: This script is provided for educational and informational purposes only. Automated posting can potentially violate platform guidelines and terms of service of both Reddit and Instagram. Make sure to review and comply with the terms of service and guidelines of both platforms before using this script. The author takes no responsibility for any misuse or violation of terms of service resulting from the use of this script.

## Contributing

Contributions are welcome! If you have any ideas for improvements, features, or find any issues, please open an issue or submit a pull request. Your contributions help make this project better for everyone.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

