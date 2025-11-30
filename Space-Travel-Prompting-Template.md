# Space Travel Booking Platform – Prompting Template (Completed Instance)

```yaml
prompting_template:
  description: "Create a Python-based web application that powers the future of space travel, allowing users to book, manage, and experience interstellar journeys from Dubai to space stations and lunar hotels. The platform blends AI-driven recommendations, predictive analytics, and immersive data visualizations, making space travel planning seamless and engaging."
  
  core_inputs:
    - departure_date: "User-selected travel date."
    - destination: "Choice of space stations, lunar hotels, or deep-space resorts."
    - seat_class: "Economy, business, or VIP zero-gravity experience."
    - traveler_type: "Business traveler, tourist, or research astronaut."
    - accommodation_preference: "Preferred orbital stay (e.g., Moon Base, Mars Habitat, or Space Capsule)."
    - budget: "User's travel budget to determine suitable packages."
    - additional_services: "Extra amenities such as EVA spacewalks, AI-guided tours, or zero-G dining."

  functionality:
    main_task: 
      name: "Trip Scheduling & Booking"
      description: "Allow users to choose departure dates, destinations, and seat classes with AI-assisted recommendations."
      predictive_need: "Optimal departure date based on space traffic, weather, and solar activity."
      ai_recommendation: "Suggest ideal travel windows and estimated flight durations based on historical patterns."
    
    secondary_task: 
      name: "Pricing & Packages"
      description: "Display and compare travel options, including economy shuttles, luxury cabins, and VIP zero-gravity experiences."
      predictive_need: "Dynamic pricing adjustments based on demand, fuel costs, and seasonal trends."
      ai_recommendation: "Highlight the best value package and notify users about limited-time offers."

    additional_feature:
      name: "Accommodation Recommendations"
      description: "Suggest suitable space hotels or orbital stations based on traveler type, preferences, and budget."
      predictive_need: "Forecast room availability and comfort levels based on AI-driven occupancy data."
      ai_recommendation: "Match users with the best accommodation, including AI-powered space concierge services."

    user_dashboard:
      name: "Traveler Dashboard & AI Insights"
      description: "A profile page where travelers can manage bookings, track launch countdowns, and get AI-based space travel tips."
      predictive_need: "Notify users about their upcoming trip with real-time countdown timers."
      ai_recommendation: "Provide personalized travel preparation tips, including space adaptation advice and health recommendations."

    example:
      input: 
        departure_date: "December 10, 2025"
        destination: "Lunar Gateway Station"
        seat_class: "VIP Zero-Gravity Experience"
        traveler_type: "Business"
        budget: "$150,000"
      output: 
        trip_duration: "4 hours to Lunar Gateway"
        best_departure_window: "Dec 8-12 (solar activity: Low)"
        pricing_trend: "🔻 Price dropped by 5% compared to last month"
        ai_tip: "Pack calcium-rich food for better bone health in low gravity."
        visualization: "A dynamic chart showing launch countdown and travel speed variations."

  creative_twist:
    name: "Orbital Speed Tracker"
    description: "An animated speed visualization reflecting real-time travel velocity, dynamically changing based on user's booked trip."
    animation: "Color-coded pulse effect based on shuttle speed: Green (Low Orbit), Blue (Lunar), Red (Deep Space)."
    visualization: "Trend chart displaying historical flight speeds compared to user’s chosen travel path."

  output:
    display: "Clean, futuristic space-themed layout with animated orbital elements and interactive data visualizations."
    elements:
      - "Trip Scheduling & Booking insights with AI predictions."
      - "Pricing trends and AI-recommended best-value packages."
      - "Accommodation suggestions based on traveler type."
      - "User Dashboard with countdown timer and health tips."
      - "Orbital Speed Tracker animation."
      - "Visual trends for travel data (departure optimization, pricing trends, speed comparisons)."
    error_handling: "Friendly, space-themed error messages (e.g., '🚀 Oops! Your space coordinates are missing! Enter a valid date and destination to continue.')"

  ui_basics:
    input_form: 
      - "Departure Date"
      - "Destination"
      - "Seat Class"
      - "Traveler Type"
      - "Budget"
      - "Additional Services"
    buttons: 
      - "Search Flights"
      - "Compare Packages"
      - "Book Now"
    display_elements: 
      - "AI-Powered Travel Insights"
      - "Launch Countdown Timer"
      - "Animated Speed & Travel Path Visuals"
      - "Dynamic Pricing Charts"

  generated_output:
    backend: "app.py with Flask or FastAPI, handling user inputs, AI-powered predictions, and real-time updates."
    frontend: "index.html with CSS/JS animations, Chart.js for dynamic visualizations, and Bootstrap for a sleek UI."
```
