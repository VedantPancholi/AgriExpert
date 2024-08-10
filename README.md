

# Farmer Support ChatBot
Farmers often struggle to get timely and accurate advice on crop management, pest control, and other agricultural practices. The existing solutions might not always be tailored to their specific needs or may be difficult to access, leading to suboptimal farming decisions.

![image](https://github.com/user-attachments/assets/bfdc2004-b2b5-4784-8507-c84b0a26033f)



## Installation

To run the code in this project, ensure you have the following dependencies:

-   Python 3
-   Flask
-   React
-   Socket IO
-   SpeechRecognition (for speech recognition)
-   Googletrans (for language translation)

You can install the required Python packages using the following commands:

```bash
pip install flask flask-socketio speechrecognition googletrans==4.0.0-rc1
```

For the React frontend, navigate to the `frontend` directory and run:

```bash
npm install
```

## Usage

1.  Clone this repository:

```bash
git clone https://github.com/your-username/Farmer-Support-ChatBot.git
```

2.  Navigate to the project directory:

```bash
cd Farmer-Support-ChatBot
```

3.  Run the Flask backend:

```bash
python chat.py
``` 

4.  Run the React frontend:

```bash
npm run build
npm run dev
```

5.  Open your browser and access `http://localhost:5173/` to interact with the Farmer Support ChatBot.
