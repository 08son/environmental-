FULL AI APP DEVELOPMENT PROMPT: ECOTRACK
Project Title
EcoTrack – Smart Waste Management and Recycling Monitoring System

1. Role and Goal
Act as a professional full-stack web developer, UI/UX designer, database engineer, and environmental sustainability expert.

Build a complete, fully functional, responsive web application named EcoTrack for my Environmental Studies (EVS) engineering college project.

The application must help individuals, students, colleges, and communities record waste generation, segregate waste into categories, monitor recycling activities, track environmental impact, and improve waste management practices.

Do not create only a static design or a non-functional prototype. Build a working application with functional buttons, forms, calculations, charts, data storage, validation, and CRUD operations.

2. Recommended Technology Stack
Use the following technologies:

Frontend: React with TypeScript.
Styling: Tailwind CSS.
Icons: Lucide React.
Charts: Recharts.
Backend and database: Supabase, if supported by the platform.
Authentication: Supabase Auth, if supported.
Alternative: If Supabase is unavailable, use a suitable backend or browser local storage for a fully usable local demonstration.
Currency and measurement units: Indian context, with waste measured in kilograms.
Language: English.
Use stable, compatible package versions and provide clear setup instructions.

3. UI/UX Design
Create a professional, modern, eco-friendly interface.

Design requirements:

Primary colors: forest green, leaf green, white, and light grey.
Use a clean dashboard layout with sidebar navigation.
Use rounded cards, subtle shadows, readable typography, and consistent spacing.
Add appropriate environmental icons.
Use responsive layouts for desktop, tablet, and mobile.
Add a light theme and optional dark theme.
Include loading indicators, empty states, confirmation dialogs, success messages, and error messages.
Provide an accessible interface with labels, keyboard navigation, and readable contrast.
Use realistic demonstration data only when clearly marked as sample data.
Do not use fake statistics presented as real environmental results.
4. Main Dashboard
Create a dashboard displaying the following statistics:

Total waste collected (kg).
Total recyclable waste (kg).
Total organic/wet waste (kg).
Total dry waste (kg).
Waste diverted from disposal (kg), based on recorded recycling or composting outcomes.
Number of waste collection records.
Recycling/diversion percentage.
Daily, weekly, monthly, and yearly waste summaries.
Add interactive charts:

Waste by category: doughnut chart.
Waste collected over time: line chart.
Waste generation by category: bar chart.
Recycling and disposal comparison: bar chart.
Waste collection trends by date.
Add date-range filters and category filters. All dashboard statistics and charts must update when records are added, edited, deleted, or filtered.

5. Waste Management Module
Create a complete waste management section.

Allow users to:

Add a new waste collection record.
View all waste records in a table.
Edit existing records.
Delete records after confirmation.
Search records.
Filter records by date, category, and status.
Sort records by date and weight.
Export records to CSV.
Each waste record must include:

Unique record ID.
Waste category.
Waste type or description.
Weight in kilograms.
Collection date and time.
Collection location.
Disposal or processing method.
Recycling/composting status.
Notes.
Created-at and updated-at timestamps.
Validate all inputs. Weight must be a positive number, required fields must not be empty, and invalid dates must be rejected.

6. Waste Categories
Provide these categories:

Wet/organic waste.
Dry waste.
Recyclable waste.
Plastic waste.
Paper and cardboard.
Glass waste.
Metal waste.
Electronic waste (e-waste).
Hazardous waste.
Other waste.
Allow users to filter and report waste by category.

Do not assume that every item in the recyclable category has actually been recycled. Track collection, recycling, composting, and disposal as distinct statuses or outcomes.

Provide appropriate safety guidance for e-waste and hazardous waste, and do not recommend mixing hazardous waste with ordinary waste.

7. Waste Collection Form
Build an attractive form with these fields:

Waste category dropdown.
Waste name or description.
Weight in kilograms.
Collection location.
Collection date.
Processing method.
Processing status.
Optional notes.
Add buttons for Save Record, Reset Form, and Cancel.

After saving:

Validate the form.
Store the record in the database or local storage.
Display a success message.
Update dashboard statistics immediately.
Refresh charts and tables automatically.
Prevent duplicate submissions where practical.
8. Recycling Monitoring Module
Create a dedicated recycling section.

Features:

Track recyclable materials collected.
Track materials sent for recycling.
Track organic waste sent for composting.
Track materials awaiting processing.
Track waste sent for disposal.
Display processing status.
Show monthly recycling and composting trends.
Identify categories with high waste generation.
Suggest appropriate waste-reduction practices.
Calculate the recycling rate using clearly defined data:

Recycling Rate (%) = Weight of waste confirmed as recycled / Total waste collected × 100.

Calculate the composting rate separately.

Calculate the diversion rate using the combined weight confirmed as recycled or composted, divided by total waste collected.

Avoid counting the same material twice. Clearly document the calculation rules and allow users to understand how each figure is derived.

9. Environmental Impact Module
Create an environmental impact page showing:

Total waste collected.
Weight of waste confirmed as recycled.
Weight of waste composted.
Waste sent for disposal.
Estimated waste diverted from disposal.
Monthly and yearly environmental trends.
Waste reduction goals.
Progress toward goals.
Add an optional carbon-emissions estimation feature only if defensible emission factors are available.

Allow administrators to configure emission factors and display the source, unit, and assumptions used.

Do not invent carbon savings, trees saved, or equivalent environmental benefits. If reliable factors are unavailable, label the feature as a demonstration estimate or omit it.

10. Smart Recommendations
Create a rule-based recommendation system that analyzes actual stored data.

Examples:

If plastic waste is high, suggest reusable alternatives and improved plastic collection.
If organic waste is high, suggest segregation and suitable composting practices.
If paper waste is high, suggest double-sided printing and paper recycling.
If recycling rates decrease, recommend reviewing collection and segregation practices.
If a waste-reduction goal is not met, show the remaining amount and practical suggestions.
Recommendations must update according to the data. Do not present fixed recommendations as AI-generated analysis.

11. Goals and Challenges
Create a goals section where users can:

Set a monthly waste-reduction target.
Set a recycling target.
Set a composting target.
View current progress.
See the remaining amount to reach each goal.
View completed and pending goals.
Calculate progress from recorded data and display progress bars.

Ensure percentages remain within a meaningful range and handle zero-value denominators correctly.

12. Reports and Analytics
Create a reports section with:

Daily waste report.
Weekly waste report.
Monthly waste report.
Yearly waste report.
Category-wise waste report.
Recycling and composting report.
Waste disposal report.
Environmental goal progress report.
Include date filters and summary statistics.

Provide CSV export. If PDF export is supported, create a printable report with the project title, selected period, summary tables, and charts.

Exports must contain actual filtered records, not hardcoded example data.

13. Search and Filters
Add global search and useful filters.

Users should be able to search by:

Waste type.
Category.
Location.
Record ID.
Processing method.
Allow sorting by date, weight, and category.

Provide a clear button to reset filters.

14. User Authentication and Roles
If backend authentication is supported, implement:

User registration.
Login and logout.
Password reset.
Protected dashboard.
User
