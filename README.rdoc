# Ticketee
Ticketee is a foundational ticket-tracking application built with Ruby on Rails 4.2. This repository provides the basic structure for building a complete ticketing system.

## Technologies Used
*   **Backend:** Ruby on Rails 4.2.5
*   **Database:** SQLite3
*   **Testing:** RSpec, Capybara
*   **Frontend:** JQuery, Sass, CoffeeScript

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

*   Ruby
*   Bundler
*   SQLite3

## Installation

1.  Clone the repository:
    ```sh
    git clone https://github.com/fathallahhassen/ticketee.git
    ```

2.  Navigate to the project directory:
    ```sh
    cd ticketee
    ```

3.  Run the setup script. This will install dependencies and prepare the database.
    ```sh
    bin/setup
    ```

4.  Start the Rails server:
    ```sh
    rails server
    ```

5.  Open your browser and navigate to `http://localhost:3000`.

## Running the Test Suite

This project uses RSpec for testing. To run the test suite, execute the following command from the root of the project:

```sh
bundle exec rspec
