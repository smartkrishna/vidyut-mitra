# VidyutMitra


You can find the live version of the platform at [vidyutmitra.vercel.app](https://vidyutmitra.vercel.app/).


# Overview
VidyutMitra addresses key challenges in energy management by tackling inefficient energy usage, underutilized solar resources, and the demand for real-time data to optimize energy costs. Designed specifically for the Indian market, VidyutMitra is an integrated platform that empowers users with effective solar energy management and intelligent power consumption solutions.

# Features
- **Real-Time Tariff Monitoring:** Track live electricity rates to optimize energy consumption.  
- **Energy Consumption Analytics:** Gain insights into energy usage patterns and identify areas for improvement.  
- **Smart Scheduling:** Automatically schedule high-energy appliances based on tariff forecasts and user preferences.  
- **Solar Energy Management:** Maximize solar energy utilization to reduce dependency on the grid.  
- **Machine Learning Forecasting:** Predict energy demand and generation to enhance efficiency.  
- **User Notifications:** Stay informed with alerts about tariff changes, peak usage, and recommended actions.  
- **Cost-Benefit Analysis:** Understand the financial impact of energy consumption and solar savings.

## Machine Learning Models

Our solution incorporates advanced machine learning to predict tariffs, solar generation, and appliance usage. Explore each model below:

- **Tariff Prediction Model**  
  Provides real-time and forecasted tariff rates to help users make cost-effective energy usage decisions.  
  [https://tariff-ghvevylojjqd2r2sogu2nx.streamlit.app/](https://tariff-ghvevylojjqd2r2sogu2nx.streamlit.app/)

- **Solar Energy Prediction Model**  
  Uses weather data to forecast solar generation, aiding users in optimal energy utilization.  
  [https://solarpre-gajvjjgbkylfkwrdt98qsd.streamlit.app/](https://solarpre-gajvjjgbkylfkwrdt98qsd.streamlit.app/)

- **Appliance Usage Analysis Model**  
  Analyzes and predicts user appliance usage patterns, enabling data-driven recommendations for savings.  
  [https://electricity-pattern-n6hwxkcjfa3wp9pepcnpdy.streamlit.app/](https://electricity-pattern-n6hwxkcjfa3wp9pepcnpdy.streamlit.app/)


## Installation

1. Clone the repository:

```
git clone https://github.com/smartkrishna/vidyut-mitra
cd vidyut-mitra
```

2. Install the required dependencies:

```
npm install # or pnpm, yarn, etc.
```

3. Add the environment variables according to the `.env.example` file:

```
cp .env.example .env
```

4. Run the application:

```
npm run dev # or pnpm dev, yarn dev, etc.
```

You can now access the application at `http://localhost:3000`.
