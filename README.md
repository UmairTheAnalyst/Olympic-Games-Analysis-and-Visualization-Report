# Olympic-Games-Analysis-and-Visualization-Report
 Analyzing Olympic data with Python using Pandas, SQL, and Matplotlib. Includes insights into medal counts, athlete performance, and historical trends through interactive visualizations.

**Purpose**
This project aims to analyze historical Olympic data to uncover insights into medal distribution, athlete performance, and trends across various Olympic Games. By leveraging data analysis and visualization techniques, the project provides a comprehensive overview of Olympic statistics.


**Datasets**
Athlete Biography: Contains information about athletes, including height, weight, and country.

Columns: athlete_id, name, sex, born, height, weight, country, country_noc, description, special_notes
Total Rows: 155,861
Athlete Event Details: Records the details of athletes' performances in various events.

Columns: edition, edition_id, country_noc, sport, event, result_id, athlete, athlete_id, pos, medal, isTeamSport
Total Rows: 316,834
Country Profiles: Contains country codes and names.

Columns: noc, country
Total Rows: 235
Event Results: Details about the results of events.

Columns: result_id, event_title, edition, edition_id, sport, sport_url, result_date, result_location, result_participants, result_format, result_detail, result_description
Total Rows: 7,394
Games Summary: Summary of each Olympic edition.

Columns: edition, edition_id, edition_url, year, city, country_flag_url, country_noc, start_date, end_date, competition_date, isHeld
Total Rows: 64
Medal Tally History: Historical medal counts by country and year.

Columns: edition, edition_id, year, country, country_noc, gold, silver, bronze, total
Total Rows: 1,807

**Important Calculations**
Top Countries by Total Medals: Identified the top 10 countries with the highest total medal counts.
Top Sports by Medal Counts: Analyzed the top 5 sports with the highest total medal counts.
Average Height and Weight by Country: Calculated average height and weight of athletes from different countries.
Medal Counts Over Years: Analyzed total medals awarded each year.
Medals by Gender: Compared medal counts between male and female athletes.
Top Cities Hosting the Olympics: Identified cities that have hosted the most Olympic Games.
Top Events by Medal Counts: Analyzed the top 10 events with the highest medal counts.
Athletes with Longest Careers: Identified athletes who have participated in the most Olympic Games.
Highest Gold Medals in a Single Year: Found the years and countries with the highest gold medal counts.

**Libraries Used**
Pandas: For data manipulation and analysis.
Matplotlib: For creating visualizations.
SQLite3: For handling SQL queries and data extraction.

**Tools Used**
Jupyter Notebook: For interactive data analysis and visualization.
GitHub: For version control and project management.
Pandoc: For converting Jupyter Notebooks to PDF format (if needed).

**Summary**
The project uses Python to analyze Olympic performance data, focusing on medal counts, athlete biographies, and historical trends. Data is processed and visualized to highlight key patterns and provide valuable insights into the performance of countries, sports, and athletes over time.


**Usage**
Run the Jupyter Notebook and execute the cells to see the data analysis and visualizations. Follow the instructions and comments in the notebook to understand the methodology and results.

**License**
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to customize this README file further to suit your project’s needs!
