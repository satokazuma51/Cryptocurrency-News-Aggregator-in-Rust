📈 Crypto News Service
A Rust-based web service that collects and displays the latest cryptocurrency news. Users can enter a cryptocurrency name or symbol to fetch recent news articles from the CryptoNews API.

🚀 Features
🔎 Search news by cryptocurrency name or symbol
🌐 Fetch articles from coinmarketcap
📰 Display title, source, date, summary, and article link
💥 Handle API rate limits and errors
🌍 Simple HTML/CSS web interface
🔐 Environment-based API key handling (.env)

🛠 Tech Stack
Backend: Rust, Actix-web, Reqwest, Tokio
Frontend: HTML + CSS + JavaScript
API Source: coinmarketcap
Environment Variables: dotenv crate

📁 Project Structure
crypto_news_service/
├── src/
│   ├── main.rs        # Server entry point
│   ├── api.rs         # API route & query logic
│   └── models.rs      # Data model & fetch logic
├── frontend/
│   ├── index.html     # Search interface
│   └── style.css      # Page styling
├── .env               # API key (not committed)
├── Cargo.toml         # Rust project config
└── README.md          # Project documentation
