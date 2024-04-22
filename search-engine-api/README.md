# Search Engine API

This is the API that interacts with the database index for my second attempt at a search engine. It takes all keywords from the query and uses TF-IDF search and Cosine similarity to order the website results and send the back to the client. The matching algorithm isn't great and so some changes are needed for this to actually work properly.

I won't lie, the code in this repository is pretty poor. Was in a bit of a rush to get this working before producing the video. PRs are definitely welcome, you might have to ping me in the Discord to get my attention though!

## Installation
Ensure that you have Rust installed and access to a postgres database with the schema referenced [here](https://github.com/conaticus/search-engine-crawler/blob/dev/README.md).

- Clone the repository
- `cargo run`

This runs in conjunction with the other two repositories:
- [Crawler](../search-engine-crawler/)
- [Client Side](../search-engine-client/)
