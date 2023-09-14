# Aloka Prompt AI

## Description
Aloka AI Prompt is an open-source AI prompting tool for the modern world to discover, create, and share creative prompts.

## Tech Stack
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
 ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
 ![OAuth](https://img.shields.io/badge/OAuth-3C4A9C?style=for-the-badge&logo=oauth&logoColor=white)
 ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## Getting Started

### Prerequisites
- Node.js and yarn installed on your local machine.
- MongoDB instance (local or cloud).
- OAuth credentials.

### Installation
1. Clone the repository:
    ```
    git clone https://github.com/alokacomputing/aloka-prompt-ai.git
    ```
2. Install the dependencies:
    ```
    cd aloka-prompt-ai
    yarn install
    ```
3. Create a `.env` file in the root directory and fill it with your MongoDB and OAuth credentials:
    ```
    GOOGLE_ID=YOUR_VALUE
    GOOGLE_CLIENT_SECRET=YOUR_VALUE
    MONGODB_URI=YOUR_VALUE
    NEXTAUTH_URL=YOUR_VALUE
    NEXTAUTH_URL_INTERNAL=YOUR_VALUE
    NEXTAUTH_SECRET=YOUR_VALUE
    ```

4. Run the development server:
    ```
    yarn dev
    ```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)