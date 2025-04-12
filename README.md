# Netflix_Insights_Report
### Dashboard Link : [View Dashboard](https://app.powerbi.com/groups/me/reports/37c4fcae-9f72-4725-ac9d-68373b251709/be44d5194675a9b4e7ae?experience=power-bi)
Netflix Insights Report is an interactive Power BI report that helps users explore Netflix content by filtering movies and TV shows based on title, release year, rating, cast, and availability by country. With a sleek, Netflix-inspired UI, this report enhances content discovery and provides a visually engaging way to analyze streaming data. 🚀

## Problem Statement

This Power BI report provides insights into Netflix's movie and TV show dataset, helping users explore details like the release year, rating, availability by country, and cast information. The report allows users to filter through Netflix's content based on multiple attributes, enhancing the discovery process and making content exploration more efficient.

By using this report, users can:
- Filter movies and TV shows based on their title.
- Identify the release year of selected content.
- View the rating (e.g., TV-MA, PG-13) of the selected title.
- Explore a brief description of the movie/TV show.
- Check the categories the content is listed under.
- See the director(s) and cast involved.
- View the countries where the selected content is available.

## Steps Followed

- **Step 1**: Loaded the Netflix dataset (CSV format) into MySQL.
- **Step 2**: Performed data cleaning by handling missing values and checking for errors.
- **Step 3**: Transformed and formatted relevant columns, such as converting date fields and categorizing ratings.
- **Step 4**: Opened Power Bi and created various visualizations to present key data points:

  - **Movie/TV Show Filter**: A dropdown selector to filter by title.
  - **Release Year & Rating**: Display cards showing the year of release and rating.
  - **Description Box**: A text area providing a summary of the selected content.
  - **Listed Categories**: A multi-category display indicating the genres or types of the selected movie/TV show.
  - **Director & Cast Information**: A panel displaying key contributors.
  - **Geographical Availability**: A map visualization highlighting where the content is available.
- **Step 5**: Applied visual-level filters to ensure relevant data is displayed dynamically based on user selections.
- **Step 6**: Designed the report theme inspired by Netflix's UI, using a dark background with red and white text for contrast and clarity.

## Key Insights

- Users can quickly filter and explore Netflix content based on different attributes.
- The report provides an intuitive and visually appealing way to interact with Netflix's dataset.
- Geographic distribution helps understand content availability across different regions.

## Visuals Used

- **Dropdown (Slicer)** for selecting Movie/TV Shows.
- **Cards** for displaying the release year and rating.
- **Text Box** for movie/show descriptions.
- **List Display** for categories, directors, and cast members.
- **Map Visualization** for content availability by country.

## Technologies Used

- **Power BI** for data visualization and report creation.
- **Power Query** for data transformation and cleaning.

## Dashboard Snap
![Image](https://github.com/user-attachments/assets/f601c631-78c8-4781-83f4-795f2f593e8e)
