## My Project

## python-whatsapp-bot

This is a simple WhatsApp bot built using Python and the Flask framework. It uses Twilio's WhatsApp API to handle messaging, and ngrok is used to expose the local Flask server for testing purposes.

## Features

- Receives and responds to WhatsApp messages.
- Uses Twilio to manage WhatsApp communication.
- Flask for creating a lightweight backend server.
- ngrok for exposing the local development server to the web.

## Technologies Used

- **Python**: For backend scripting.
- **Flask**: A lightweight web framework for handling routes and HTTP requests.
- **Twilio**: For managing WhatsApp messaging via API.
- **ngrok**: To expose the local Flask server to the web for testing.

## 🌐 Socials:

[![Upwork](https://img.shields.io/badge/upwork-%2230175C2.svg?logo=Upwork&logoColor=green)](https://www.upwork.com/freelancers/~01b8262a0ffa2f4860)
[![fiverr](https://img.shields.io/badge/fiverr-%230769AD.svg?logo=fiverr&logoColor=green)](https://www.fiverr.com/gold_medalist?source=gig_page)

## 💻 Tech Stack:

![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=white)
![React.js](https://img.shields.io/badge/React.js-%2361DAFB.svg?style=for-the-badge&logo=React&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-%23000000.svg?style=for-the-badge&logo=Next.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-%234FC08D.svg?style=for-the-badge&logo=Vue.js&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-%23764ABC.svg?style=for-the-badge&logo=Redux&logoColor=white)
![Redux Thunk](https://img.shields.io/badge/Redux_Thunk-%23764ABC.svg?style=for-the-badge&logo=Redux&logoColor=white)
![Redux-Toolkit](https://img.shields.io/badge/Redux_Toolkit-%23764ABC.svg?style=for-the-badge&logo=Redux&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-%23F3B71B.svg?style=for-the-badge&logo=React&logoColor=white)
![Formik](https://img.shields.io/badge/Formik-%2361DAFB.svg?style=for-the-badge&logo=Formik&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-%2361DAFB.svg?style=for-the-badge&logo=React&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=HTML5&logoColor=white)
![HTML](https://img.shields.io/badge/XHTML-%23F58025.svg?style=for-the-badge&logo=HTML5&logoColor=white)
![CSS/CSS3](https://img.shields.io/badge/CSS/CSS3-%231572B6.svg?style=for-the-badge&logo=CSS3&logoColor=white)
![SASS/LESS](https://img.shields.io/badge/SASS/LESS-%23CC6699.svg?style=for-the-badge&logo=SASS&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-%230769AD.svg?style=for-the-badge&logo=jQuery&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-%23563D7C.svg?style=for-the-badge&logo=Bootstrap&logoColor=white)
![Material-UI](https://img.shields.io/badge/Material_UI-%231976D2.svg?style=for-the-badge&logo=Material-UI&logoColor=white)
![AntD](https://img.shields.io/badge/AntD-%230170FE.svg?style=for-the-badge&logo=Ant-Design&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-%2338B2AC.svg?style=for-the-badge&logo=Tailwind-CSS&logoColor=white)
![Node JS](https://img.shields.io/badge/Node_JS-%23339933.svg?style=for-the-badge&logo=Node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-%23000000.svg?style=for-the-badge&logo=Express&logoColor=white)
![Nest.js](https://img.shields.io/badge/Nest.js-%23E0234E.svg?style=for-the-badge&logo=NestJS&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-%E10098.svg?style=for-the-badge&logo=GraphQL)
![Prisma.js](https://img.shields.io/badge/Prisma.js-%2D2D2E2E.svg?style=for-the-badge&logo=Prisma)
![MySQL](https://img.shields.io/badge/MySQL-%4479A1.svg?style=for-the-badge&logo=MySQL)
![MongoDB](https://img.shields.io/badge/MongoDB-%47A248.svg?style=for-the-badge&logo=MongoDB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%336791.svg?style=for-the-badge&logo=PostgreSQL)

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

- [Python](https://www.python.org/downloads/) (version 3.7 or higher)
- [Twilio Account](https://www.twilio.com/try-twilio) (for WhatsApp integration)
- [ngrok](https://ngrok.com/) (for exposing your local server)

### Installation

1. Clone the repository:

   - git clone https://github.com/yourusername/python-whatsapp-bot.git
   - cd python-whatsapp-bot
   - python -m venv venv
   - source venv/bin/activate
   - pip install -r requirements.txt
   - TWILIO_ACCOUNT_SID=your_twilio_account_sid
   - TWILIO_AUTH_TOKEN=your_twilio_auth_token
   - TWILIO_PHONE_NUMBER=your_twilio_whatsapp_number
   - flask run
   - By default, the Flask server runs on http://127.0.0.1:5000/.
   - ngrok http 5000
