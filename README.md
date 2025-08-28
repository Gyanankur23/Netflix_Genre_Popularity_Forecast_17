# Netflix_Genre_Popularity_Forecast_17 CaseCraft Analytics Project Sprint Project 17


## 🎬 Overview  
This project forecasts Netflix genre popularity using synthetic viewing data and time series modeling. It blends Prophet forecasting, streamgraphs, ridge plots, and regression modeling to guide content strategy and scheduling.

## 🎯 Objective  
To model genre-level watch hour trends, visualize engagement evolution, and predict future popularity using temporal and genre features.

## 📺 Dataset & Features  
- Genres: Drama, Comedy, Thriller, Romance, Sci-Fi, Documentary  
- Dates: Jan–Jun 2023 (180 days)  
- Features: watch_hours, viewer count, engagement rate  
- Derived: lag features, genre encoding

## 📊 Visual Explorations  
- **Streamgraph**: Genre watch hours over time  
- **Ridge Plot**: Genre engagement distribution  
- **Calendar Heatmap**: Daily total watch hours  
- **Prophet Forecast**: Drama genre projection  
- **Scatterplot**: Predicted vs Actual watch hours

## 🔮 Forecasting & Modeling  
- **Prophet**: Time series forecast for Drama genre  
- **Regression Model**:  
  - Input: genre, day of year, lag_1 watch hours  
  - Target: next-day watch hours  
  - Model: Random Forest Regressor  
  - Performance: MAE ≈ **519.75 watch hours**

## 🧠 Key Insights  
1. **Genre Spikes**: Drama and Sci-Fi show strong seasonal surges  
2. **Engagement Variance**: Thriller has highest variance in watch hours  
3. **Temporal Patterns**: Weekend spikes visible in calendar heatmap  
4. **Forecast Alignment**: Prophet and regression models show consistent trends  
5. **Strategic Utility**: Enables scheduling, genre prioritization, and content planning

## ✅ Final Conclusion  
Netflix genre forecasting reveals clear temporal and engagement patterns. This framework supports content scheduling, genre targeting, and strategic planning—ideal for media teams optimizing viewer engagement and release timing.