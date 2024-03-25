# Cyclistic Bike-Share Analysis

## Description
Analyzing bike-share usage patterns at Cyclistic to optimize marketing strategies & maximize revenue. Project for Google Data Analytics Certification. [Case Study.pdf](Case%20Study.pdf).

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Roadmap](#roadmap)
- [Presentation](#presentation)
- [Contributing](#contributing)
- [License](#license)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/CodeDavila/cyclistic-bike-share-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd cyclistic-bike-share-analysis
    ```
3. Ensure you have R and RStudio installed on your machine.
4. Open the R project file (.Rproj) in RStudio.
5. Install any required R packages using `install.packages("package_name")`.

## Usage
The complete report is in the bike_share_report.html under the R_Files directory.

## Data
The data used for this analysis was sourced from the Divvy Bikes System Data, specifically the Historical trip data available to the public. Key details about the data:
- Data Source: Divvy Data (Historical trip data available to the public: Divvy Bikes System Data)
- Content: Anonymized trip information including trip start and end times, start and end stations, and rider type (Member and Casual riders [Single Ride, Day Pass]).
- Data Processing: Trips taken by staff for servicing and inspection purposes were removed. Trips with durations below 60 seconds were filtered out.
- Access: The data was available for public use according to the Divvy Data License Agreement and released on a monthly schedule.
- Data Period: Data was imported for the first quarters of 2019 and 2020.
- source: [Divvy Bikes](https://divvybikes.com/system-data)

## Analysis
Here's a summary of the analysis conducted:
1. **Usage Frequency:** We calculated the usage frequency for annual members and casual riders by counting the number of rides for each member type.
2. **Trip Duration:**
   - We calculated the average trip duration ("ride length") for each member type.
   - We compared the average trip durations between annual members and casual riders to determine if they tend to take shorter or longer rides on average.
3. **Popular Routes and Stations:**
   - We identified popular start and end stations for each member type by counting the occurrences of each station.
   - We analyzed whether annual members and casual riders tended to ride in different areas of the city by comparing the density of rides originating from each station between the two groups.

## Results
### Key Findings:
- **Usage Frequency:**
  - Annual members: 720,312 rides
  - Casual riders: 67,877 rides
  - **Insight:** Annual members use Cyclistic bikes significantly more frequently than casual riders.
- **Trip Duration:**
  - Casual riders: Average duration of approximately 89.55 minutes
  - Annual members: Average duration of approximately 13.25 minutes
  - **Insight:** Casual riders tend to take longer trips compared to annual members.
- **Popular Routes and Stations:**
  - Top start and end stations for annual members: Canal St & Adams St
  - Top start and end stations for casual riders: Streeter Dr & Grand Ave
  - **Insight:** Distinct preferences in station usage are observed between annual members and casual riders.


## Technologies Used
- R
- RStudio

## Roadmap
The complete roadmap is available in the file [Case Study Roadmap.pdf](Case%20Study%20Roadmap.pdf).

## Presentation
The presentation containing visualizations and key findings is available in either [Understanding Cyclistic Bike Usage.ppt](Understanding%20Cyclistic%20Bike%20Usage.ppt) or [Understanding Cyclistic Bike Usage.pdf](Understanding%20Cyclistic%20Bike%20Usage.pdf).

## Contributing
Contributions are welcome! Here's how you can contribute:
1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License
This project is part of the Google Data Analytics Professional Certificate program offered on Coursera. You are free to use and modify the code and analysis for educational and personal purposes as outlined in the course. However, if you intend to use this project for commercial purposes or distribution, please make sure to adhere to the terms and conditions set by Google and Coursera.
