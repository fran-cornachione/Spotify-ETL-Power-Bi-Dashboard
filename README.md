# Spotify Playlist Analysis Dashboard

This project is an interactive **Power BI** dashboard built using data from my personal Spotify account. It showcases key insights such as:

- Most played tracks
- Top artists
- Most popular artists
- Average song duration
- Longest song
- Shortest song

## Technologies Used

- **Power BI** – Data visualization
- **Python** + [Spotipy](https://spotipy.readthedocs.io/en/2.22.1/) – Data extraction from Spotify API
- **.env file** – Secure storage of credentials (ignored in Git)
- **Git & GitHub** – Version control and hosting

## Project Structure

📁 **data/:** Raw or processed CSV files

📁 **notebooks:** Python notebooks for data extraction and transformation

📁 i**nfo/:** Instructions and README.md

📄 **.env:** Environment variables (ignored)

📄 **.gitignore:** .env

📄 **tech.pbix:** Power BI file

📄 **README.md:** Current file

## 📊 Dashboard Preview

![1747585077693](image/README/1747585077693.png "Dashboard Preview")

## ▶️ How to Run

1. Clone this repository
2. Create a `.env` file in the root directory with your Spotify credentials:
   ```env
   CLIENT_ID=your_client_id
   CLIENT_SECRET=your_client_secret
   REDIRECT_URI=http://127.0.0.1:8888/callback
   ```
3. Run the notebook inside `notebooks/` to extract and save the data (Run All)
4. Now, you can make a `.pbix` file, and visualize your data.

## 🎯 Purpose

This project was created for **learning** and **portfolio** purposes, and to showcase my skills in:

- API-based data extraction
- Data cleaning and transformation
- Power BI dashboard design
- Clean Git/GitHub project structure

📬 Contact

Feel free to connect or reach out:

[LinkedIn](linkedin.com/in/francesco-cornachione-78bb4727a/)
[GitHub](https://github.com/fran-cornachione)

[Mail](francescocornachione681@gmail.com)
