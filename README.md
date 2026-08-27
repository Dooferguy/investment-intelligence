# Investment Intelligence

Investment Intelligence is a personal, non-commercial Windows desktop application for investment research and market analysis.

The application combines information from multiple public data sources to help identify market trends, company discussion activity, sentiment changes, and potentially relevant investment research signals.

## Reddit API Use

The application intends to use Reddit's API for read-only access to publicly available Reddit content.

Reddit data may be used to:

* Identify mentions of publicly traded companies and stock tickers
* Measure changes in discussion volume
* Analyze general sentiment and discussion trends
* Identify potentially important market-related conversations
* Compare Reddit discussion signals with other public market and news information

The application may access public posts, public comments, subreddit information, and associated public metadata from finance and investment-related communities.

Example communities may include:

* r/stocks
* r/investing
* r/StockMarket
* r/wallstreetbets
* r/SecurityAnalysis

## Read-Only Operation

The application does not require Reddit permissions to:

* Create posts
* Create comments
* Vote
* Send private messages
* Perform moderation actions
* Automatically interact with Reddit users

Reddit access is intended to be read-only.

## Application Architecture

Investment Intelligence runs locally as a standalone Windows desktop application.

Its user interface, database, analysis systems, market-data processing, and other research features operate outside of Reddit. This is why the application requires external API access rather than operating as a Devvit application within Reddit.

## Data Use

Reddit content is intended to be used as one informational research signal alongside other public market and news sources.

The application is not intended to sell or redistribute Reddit content.

Reddit content is not intended to be used to train a general-purpose artificial intelligence model.

## Project Status

This repository provides public documentation for the Investment Intelligence application and its intended Reddit API integration.

The main application is currently under private development and runs locally on Windows.
# investment-intelligence
Personal non-commercial investment research and market intelligence application.
