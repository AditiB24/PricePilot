# Price Pilot - A Price Comparison Website

**Price Pilot** is a web application developed to help users compare the prices of products across multiple e-commerce platforms. This tool assists users in making informed purchasing decisions by scraping and displaying price listings from a selection of popular e-commerce websites.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Motivation](#motivation)
- [System Architecture](#system-architecture)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Future Scope](#future-scope)
- [Limitations](#limitations)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

In today's e-commerce landscape, there are numerous websites that offer the same products at different prices. As a solution to this issue, **Price Pilot** provides a price comparison tool where users can search for a product and view price listings from multiple e-commerce websites like Amazon, Flipkart, Jio Mart, etc., all in one place. 

This application aims to simplify the purchasing process by saving users the time and effort it takes to manually check prices across different websites.

## Features
- **Search for Products**: Users can search for products by entering product names.
- **Price Comparison**: Compare the prices of a product from different e-commerce platforms.
- **Single Page View**: All information and functionalities are presented on a single webpage to save user time and make navigation easier.
- **No Account Needed**: Users can use the application without the need to sign up or log in, ensuring privacy and ease of access.

## Motivation

Many e-commerce websites offer varying prices for the same products, and users often end up paying more than necessary. This project aims to solve this problem by introducing **Price Pilot**, where users can compare product prices across different websites. The goal is to help users make informed decisions by displaying all available options in one place.

## System Architecture

The system is divided into three key modules:
1. **Input Module**: Where users input the product name.
2. **Scraping Module**: This module scrapes product price data from selected e-commerce websites.
3. **Display Module**: Displays the scraped prices in a user-friendly manner.

### Flow Chart

![Flow Chart](path_to_flowchart_image)

### Block Diagram

![Architectural Block Diagram](path_to_architecture_image)

## Technologies Used

- **Backend**: Python (Django Framework)
- **Frontend**: HTML, CSS, JavaScript
- **Web Scraping**: BeautifulSoup4

## Installation and Setup

### Prerequisites
- Python 3.x
- Django 3.x
- `beautifulsoup4` library for web scraping

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/price-pilot.git
   cd price-pilot
