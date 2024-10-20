# Food Delivery Chatbot

## Overview

The **Food Delivery Chatbot** is an intelligent conversational agent designed to enhance the online food ordering experience. Built using **Dialogflow**, **FastAPI**, and a SQL database, this chatbot streamlines the ordering process by allowing users to place orders, track deliveries, and receive personalized recommendations—all through natural language interactions.

## Features

- **Natural Language Processing**: Understands user queries and responds in real-time, making the ordering process smooth and intuitive.
- **Order Placement**: Users can easily place food orders by interacting with the chatbot, specifying their preferences, and receiving confirmations.
- **Order Tracking**: Customers can track the status of their orders and receive updates on delivery times.
- **Personalized Recommendations**: Based on user preferences and order history, the chatbot offers customized meal suggestions.

## Technologies Used

- **Programming Languages**: Python
- **Frameworks**: FastAPI for backend development
- **Natural Language Processing**: Dialogflow for understanding user intents and entities
- **Database**: SQL for storing user data, order history, and menu items

## Getting Started

### Prerequisites

To run the Food Delivery Chatbot locally, you will need:

- Python 3.7 or higher
- Required libraries (install via `requirements.txt`)
- A Dialogflow account to create and manage intents and entities

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/food-delivery-chatbot.git
   cd food-delivery-chatbot
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up the Dialogflow webhook URL to point to your FastAPI application.

4. Start the application:

   ```bash
   uvicorn main:app --reload
   ```

5. Access the chatbot through your preferred interface or integrate it into a food delivery website.

## Usage

- Interact with the chatbot via a web interface or messaging platform.
- Users can ask questions like:
  - "I'd like to order a pizza."
  - "What are today’s special offers?"
  - "Track my order status."

## Contributing

Contributions are welcome! If you have suggestions or improvements for the Food Delivery Chatbot, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or feedback, feel free to reach out:

- Email: raghavkhandelwal39@gmail.com
- LinkedIn: [LinkedIn profile(https://www.linkedin.com/in/raghav-khandelwal-a42545228/)]
