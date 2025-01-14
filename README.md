# **Healthcare AI Agent**

A React-based web application that provides healthcare-related assistance powered by the OpenAI ChatGPT API. Users can ask health-related questions, and the app responds with helpful and formatted advice in a tabular format.

---

## **Features**

- **AI-Powered Assistance**: Uses OpenAI's GPT-3.5/4 to provide accurate healthcare advice.
- **User-Friendly Interface**: Simple and intuitive text input and response display.
- **Formatted Responses**: Presents AI-generated advice in a tabular format for better readability.
- **Secure Configuration**: API key management using environment variables.
- **Error Handling**: Displays clear messages for invalid inputs or API errors.

---

## **Technologies Used**

- **Frontend**: React.js
- **Backend API**: OpenAI ChatGPT API
- **Styling**: CSS
- **Environment Management**: `.env` for sensitive data

---

## **Installation and Setup**

### **1. Clone the Repository**
```bash
git clone https://github.com/thekartikeyamishra/healthcare-ai-agent.git
cd healthcare-ai-agent
```

### **2. Install Dependencies**
Ensure you have [Node.js](https://nodejs.org/) installed. Then, run:
```bash
npm install
```

### **3. Set Up API Key**
1. Create a `.env` file in the project root:
   ```bash
   touch .env
   ```
2. Add your OpenAI API key to the `.env` file:
   ```plaintext
   REACT_APP_OPENAI_API_KEY=your_openai_api_key_here
   ```

### **4. Start the Development Server**
```bash
npm start
```
The app will be available at `http://localhost:3000`.

---

## **How to Use**

1. **Enter a Query**: Type a healthcare-related question in the input box (e.g., "What are the symptoms of a cold?").
2. **Get Response**: Click on the "Get Response" button.
3. **View Results**: The AI-generated response will be displayed in a formatted table below the input box.

---

## **Demo**

You can find a live demo of the application [here](#) (update with your live deployment link).

---

## **Project Structure**

```
healthcare-ai-agent/
│
├── public/
│   ├── index.html          # Main HTML file
│   ├── favicon.ico         # Favicon
│
├── src/
│   ├── components/
│   │   └── HealthcareAgent.js   # Main AI Agent Component
│   │
│   ├── App.js                   # Main App Component
│   ├── index.js                 # Entry Point for React App
│   └── styles.css               # Custom Styles
│
├── .env                         # Environment Variables (Not committed to Git)
├── .gitignore                   # Git Ignore File
├── package.json                 # Project Dependencies
└── README.md                    # Project Documentation
```

---

## **Environment Variables**

| Key                     | Description                          |
|-------------------------|--------------------------------------|
| `REACT_APP_OPENAI_API_KEY` | Your OpenAI API key for the ChatGPT API |

---

## **Deployment**

### **Deploy to Netlify**
1. Install Netlify CLI:
   ```bash
   npm install -g netlify-cli
   ```
2. Build the project:
   ```bash
   npm run build
   ```
3. Deploy the build folder:
   ```bash
   netlify deploy
   ```
4. Add `REACT_APP_OPENAI_API_KEY` in the environment variable settings on Netlify.

### **Deploy to Vercel**
1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```
2. Deploy the project:
   ```bash
   vercel
   ```
3. Add `REACT_APP_OPENAI_API_KEY` in the environment variable settings on Vercel.

---

## **Examples**

### **Input**
> What are the symptoms of a cold?

### **Output**
| **Field**                          | **Details**                                                        |
|------------------------------------|--------------------------------------------------------------------|
| Symptom 1                          | Sneezing                                                           |
| Symptom 2                          | Runny nose                                                         |
| Symptom 3                          | Sore throat                                                        |
| Symptom 4                          | Mild headache                                                      |
| Advice                             | Rest, stay hydrated, and take over-the-counter medication if needed.|

---

## **Troubleshooting**

### **Common Issues**
1. **Error: "API key is missing. Check your .env file."**
   - Ensure the `.env` file is created and contains the correct API key.
   - Restart the development server after adding the `.env` file.

2. **Error: "Failed to fetch AI response."**
   - Verify your OpenAI API key is valid and has sufficient credits.
   - Check your network connection.

3. **Blank or Unexpected Responses**
   - Ensure the question is clear and concise.
   - Try rephrasing the query for better results.

---

## **Contributing**

Contributions are welcome! If you would like to contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Acknowledgments**

- [OpenAI](https://openai.com/) for the ChatGPT API.
- React.js community for providing excellent documentation and tools.

---

Let me know if you need further assistance!
