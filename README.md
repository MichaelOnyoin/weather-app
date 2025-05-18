# Weather App
### The Weather App is a simple application that displays the current weather for a given location. The application uses the OpenWeatherMap API to fetch the weather data. The user can input  their location and the application will display the current weather conditions, temperature, and a 3-day forecast.

## Frontend 
<p>The frontend is built using the NextJS Framework with typescript </p>
<img src="Screenshot 2025-05-17 233309.png" alt="Weather App screenshot" style="height:500px; width:700px;"/>
<br>
<p>Running the frontend</p>

```bash
cd frontend
# next
npm install
# then
npm run dev
# or
pnpm dev
# or
bun dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
Search [weather-frontend](https://github.com/MichaelOnyoin/weather-frontend) with your browser to check the github source code for the web NextJS frontend.
<p>Link to production ready web app project here: <a href="https://weather-frontend-lime-rho.vercel.app/">weather-frontend</a></p>

## Backend 
<p>Backend is built using laravel php to produce the API endpoints</p>
<p>Running the backend</p>

```bash
cd backend
# next
composer install
#then
php artisan serve
```
Open [http://localhost:8000](http://localhost:8000) with your browser to see the resulting the api interface.<br>
Search [http://localhost:8000](http://localhost:8000/api/weather?city=Nairobi&units=metric) with your browser to see the api endpoints for Nairobi city.<br>
Search [http://localhost:8000](https://github.com/MichaelOnyoin/weather-backend) with your browser to see the github source for the laravel backend.<br>
Search [laravel-backend](https://weather-backend-master-bkxef2.laravel.cloud/api/weather?city=Kampala&units=metric) to see the production ready laravel backend

