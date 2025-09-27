# GitHub Stargazer Fetcher (Rust)

This project is a simple Rust demo that fetches the list of **stargazers** (users who starred a repository) from the GitHub API.  
It uses [`reqwest`](https://crates.io/crates/reqwest) for making HTTP requests and [`serde`](https://crates.io/crates/serde) for JSON deserialization.

---

## ✨ Features
- Makes an asynchronous HTTP GET request to the GitHub API.
- Uses a custom `User-Agent` (required by GitHub).
- Parses the JSON response into a strongly typed Rust struct.
- Prints out the list of users (`login` and `id`).

---

## 🚀 Getting Started

### Prerequisites
- [Rust](https://www.rust-lang.org/) installed (via `rustup` is recommended).
- A stable internet connection (the program queries GitHub’s API).
