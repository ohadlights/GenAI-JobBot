GenAI-JobBot
Harnessing the power of Generative AI to automate job applications on LinkedIn.

Description
GenAI-JobBot is a Python application designed to automate the job application process on LinkedIn. Using Generative AI, it fills in the necessary details and applies for positions seamlessly.

Features
Automates job applications on LinkedIn

Uses Generative AI to fill in application questions

Customizable for different job search criteria

Setup
Prerequisites
Python 3.8+

LinkedIn account

Installation
Clone the repository:

bash

Copy
git clone https://github.com/yourusername/GenAI-JobBot.git
cd GenAI-JobBot
Create a virtual environment:

python -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`

Install the required packages:
python .\update_packages.py

Configuration
Create a .env file based on the template .env.template and fill in the relevant details:

ENV=production/langtrace
LANGTRACE_API_KEY=LANGTRACE_API_KEY
LINKEDIN_EMAIL=LINKEDIN_EMAIL
LINKEDIN_PASSWORD=LINKEDIN_PASSWORD
LLM_API_KEY=LLM_API_KEY
LLM_MODEL_NAME=gpt-4o-mini
MODE=apply/reapply/reconnect
DATABASE_URL=URL

Usage
Run the application:
python main.py
The application will automatically log in to LinkedIn and start applying for jobs based on your configuration.

License
This project is licensed under the MIT License.

Contributing
Contributions are welcome! Please read the CONTRIBUTING.md for details on the process for submitting pull requests.

Contact
For any questions or feedback, please contact me at roy.meshulam@gmail.com