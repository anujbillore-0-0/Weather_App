# **Weather App**  

## **Overview**  
This is a **Weather App** built using **Vanilla JavaScript, HTML, and SCSS**. The application retrieves weather data using the **OpenWeatherMap API** and features a **mobile-first, responsive web design**.  
![image](https://github.com/user-attachments/assets/dddef16d-1d6d-415c-ab18-eaf76fcfe784)
![image](https://github.com/user-attachments/assets/c8132b87-d17c-468a-a457-07cff547e693)


## **Features**  
- **Live Weather Data**: Fetches real-time weather information from the OpenWeatherMap API.  
- **Geolocation API**: Detects the user's current location to display local weather.  
- **Search Functionality**: Users can search for weather details of any city.  
- **Persistent Data Storage**: Saves the last searched location for quick access.  
- **Fetch API with Async/Await**: Efficiently handles API requests.  
- **Accessibility Considerations**: Ensures an inclusive user experience.  
- **Serverless Functions**: Implements backend logic using Netlify serverless functions.  
- **Netlify Deployment**: Hosted and deployed on Netlify for seamless access.  

## **Prerequisites**  
Before running the application, ensure you have:  
- **Node.js** (for local development and Netlify CLI)  
- **An OpenWeatherMap API Key**  

## **Installation**  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Set up OpenWeatherMap API**  
   - Create a `.env` file in the project root.  
   - Add the API key:  
     ```plaintext
     VITE_WEATHER_API_KEY=your_api_key_here
     ```

4. **Run the project locally**  
   ```bash
   npm run dev
   ```

5. **Deploy on Netlify**  
   - Install Netlify CLI (if not installed):  
     ```bash
     npm install -g netlify-cli
     ```  
   - Deploy using:  
     ```bash
     netlify deploy
     ```  
