# Tableau Customization Map (Grouping)

An interactive choropleth map of the United States, built across two 
sheets to demonstrate custom geographic grouping and data labeling 
in Tableau.

## 🔗 Live Interactive Dashboard
[View on Tableau Public](https://public.tableau.com/app/profile/kaung.khant.han/vizzes)

## 🛠 Tools & Techniques Used
- **Tableau Desktop / Tableau Public** for map creation and publishing
- **Custom state grouping**: manually grouped all 50 states into 4 
  regions (Alabama/Connecticut group, Arizona/Arkansas/Louisiana group, 
  California/Colorado group, Illinois/Indiana/Iowa group) using 
  Tableau's Group feature, rather than the default US region breakdown
- **Color encoding**: each group assigned a distinct color for 
  quick visual comparison across the map
- **Geographic mapping**: used Tableau's built-in geocoding 
  (auto-generated latitude/longitude) to plot state boundaries
- **Data labels**: state-level values for "Percent - 2012" displayed 
  directly on the map for at-a-glance reading
- **Tooltips**: hovering a state reveals its group membership, 
  generated coordinates, and metric value

## 📌 Sheet Breakdown
- **Sheet 1**: Base choropleth showing the 4 custom state groupings 
  by color, no data labels
- **Sheet 2**: Builds on Sheet 1 by adding per-state value labels 
  and interactive tooltips (state name, group, coordinates, metric)

## 📂 Dataset
Feel free to use the dataset in this repo for your own practice or projects.
