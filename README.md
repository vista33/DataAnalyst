## Smart Building Data Analyst Assignment

### Objective
This assignment is designed to assess your ability to clean, analyze, and visualize smart building data. The dataset provided contains Indoor Air Quality (IAQ) and occupied status of meeting rooms in a flexible office space. Your task is to analyze the dataset, ensure its accuracy, and present key insights through a small dashboard.

### Target Audience
The target audience for this analysis is the property manager of the building. A property manager is responsible for overseeing and managing real estate properties. Their responsibilities include ensuring the buildings are well-maintained, addressing tenant concerns, managing budgets, and optimizing the use of spaces to improve overall efficiency and comfort.

### Tasks
1. Data Analysis & Trend Identification
   - Identify patterns and trends in IAQ and occupancy data.
   - Analyze how IAQ is influenced by room occupancy.

2. Data Visualization and/or Dashboard Creation
   - Develop a small dashboard / visual containing key graphs and trend analysis.
   - Ensure clarity and effectiveness in conveying insights.

3. Presentation of Findings
   - Summarize your key insights in a concise report.
   - Explain your thought process behind data cleaning, analysis, and visualization choices.
   - Be prepared to discuss your approach during a follow-up meeting.
 
### Dataset Description
Length: 			1 month of data.

The dataset contains the following columns:
- Timestamp: 		Date and time of the reading.
- Id: 				Unique identifier for each sensor or data point.
- Key: 				Type of measurement or data unit.
- Value: 			The recorded measurement or value.

The `Key` column includes the following units:
- Temperature: Measurement of the air temperature in degrees Celsius or Fahrenheit.
- Humidity: Measurement of the moisture content in the air, expressed as a percentage.
- Lightintensity: Measurement of the light level in the room, usually in lux.
- Movement: Detection of motion within the room, typically represented as boolean (e.g., 0 for no movement, 1 for movement).
- TVOC (Total Volatile Organic Compounds): Measurement of the concentration of volatile organic compounds in the air, usually expressed in parts per billion (ppb).
- IAQ (Indoor Air Quality): Index representing the overall air quality within the room based on various factors.
- eCO2 (Equivalent Carbon Dioxide): Measurement of the estimated CO2 concentration based on TVOC levels, expressed in parts per million (ppm).
- CO2: Direct measurement of carbon dioxide levels in the air, expressed in parts per million (ppm).
- Occupancy: Status indicating whether the room is occupied or not, typically represented as boolean (e.g., 0 for unoccupied, 1 for occupied).
- Comfort_score: Composite score representing the overall comfort level in the room, based on various environmental factors such as temperature, humidity, and air quality.

