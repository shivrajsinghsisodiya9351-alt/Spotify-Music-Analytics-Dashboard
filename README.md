# 🎧 Spotify Music Analytics Dashboard | Power BI

![Home](https://github.com/shivrajsinghsisodiya9351-alt/Spotify-Music-Analytics-Dashboard/blob/main/Home.png) ![Overview](https://github.com/shivrajsinghsisodiya9351-alt/Spotify-Music-Analytics-Dashboard/blob/main/Overview.png) ![Artists](https://github.com/shivrajsinghsisodiya9351-alt/Spotify-Music-Analytics-Dashboard/blob/main/Artist.png) ![Songs](https://github.com/shivrajsinghsisodiya9351-alt/Spotify-Music-Analytics-Dashboard/blob/main/Artist.png)

*(Pages: Home → Overview → Artists → Songs)*

## 📌 Project Description
An interactive Power BI dashboard built on Spotify streaming data covering **342 distinct artists** and **789 distinct songs**. The dashboard breaks down catalog composition, popularity trends, and release patterns across four dedicated pages — Home (navigation), Overview (KPI summary), Artists (artist-level performance), and Songs (song-level performance) — helping uncover which artists, albums, and song types drive the most engagement.

## 📊 Key KPIs
| KPI | Value |
|---|---|
| Distinct Artists | 342 |
| Distinct Songs | 789 |
| Average Popularity | 89.62 |
| Popularity Trend (YoY) | 89.62 |

## ⚙️ Process
- **Data Collection** – Sourced raw song/artist/album metadata (song name, artist, album type, duration, popularity, release date) in a Spotify-style dataset.
- **Data Preparation** – Structured song, artist, and album fields into analysis-ready tables; standardized date and duration formats.
- **Data Cleaning** – Handled missing/duplicate song-album entries, corrected explicit-content flags, and validated popularity score ranges.
- **Data Modeling** – Built relationships between Songs, Artists, and Albums; created DAX measures for distinct counts, sum of popularity, and average duration.
- **Dashboard Development** – Designed 4 pages (Home, Overview, Artists, Songs) with KPI cards, bar/donut/line charts, and a song/artist selector panel with album art.
- **Testing & Deployment** – Validated cross-filtering between pages, checked slicer interactions (song ↔ artist), and published the final `.pbix`.

## ❓ Business Questions Answered
- Which artists have released the most distinct songs, and which are the most popular by total popularity score?
- How does album count and average popularity compare across top artists (e.g., Taylor Swift vs. Billie Eilish vs. Drake)?
- What share of the catalog is singles vs. albums, and explicit vs. non-explicit content?
- How does average song popularity vary month-to-month or by quarter?
- Which specific songs/albums have the highest average duration, popularity, and most recent release dates?

## 🔎 Observations and Data Highlights
- **Taylor Swift** leads by a wide margin — highest distinct song count (85), highest album count (1,854), and highest cumulative popularity (164K).
- Singles (269) are outnumbered by albums (562) in the catalog, yet singles tend to post higher average popularity per release.
- **Non-explicit songs (17K)** outweigh explicit songs (11K), indicating the catalog skews toward broader-audience content.
- Release volume is fairly balanced across years — 423 songs in 2023 vs. 452 in 2024.
- Average popularity by month shows a dip mid-year (around Feb–Mar and Jul–Aug) and peaks near May and Oct–Nov, suggesting seasonal listening/release patterns.

## 📈 Visuals and Analytics Used
- KPI Cards – Distinct Artists, Distinct Songs, Average Popularity, Popularity Trend
- Horizontal Bar Charts – Songs by Artist, Artist by Popularity, Artist by Album Count, Songs by Popularity
- Donut Charts – Distinct Songs by Album Type, Explicit vs. Non-Explicit, Songs by Year, Average Popularity by Album Type
- Line Chart with Toggle – Average Popularity by Month/Quarter
- Column Chart – Distinct Songs by Month
- Detail Tables – Song-level and Artist-level metrics (Album Count, Avg Duration, Avg Popularity, Newest Release Date)
- Interactive Song/Artist Selector Panel with album artwork and a mock playback control
- Page Navigation Buttons (Home, Overview, Artists, Songs)

## 💡 Actionable Insights
- A small set of top artists (Taylor Swift, Billie Eilish, Sabrina Carpenter) contribute a disproportionate share of total popularity — prioritizing these for playlist placement can maximize engagement.
- Singles show stronger average popularity efficiency than albums — a single-first release strategy may outperform full-album drops for building traction.
- The dominance of non-explicit content suggests curated playlists targeting broader/family audiences have a larger catalog to draw from.
- Monthly popularity dips point to specific low-engagement windows — release timing could be shifted to avoid these troughs.

## 🎯 Expected Outcomes
- Faster identification of top-performing artists and songs for marketing/playlist decisions.
- Clear visibility into catalog composition (singles vs. albums, explicit vs. non-explicit) to guide content strategy.
- A reusable template for tracking song/artist popularity trends over time as new data is added.

## ✅ Conclusion
This dashboard turns raw song and artist metadata into a decision-ready view of catalog performance — highlighting which artists and release types drive popularity, how explicit content splits the catalog, and how engagement shifts across the year. It's built to scale with new data drops and support both marketing and content-strategy decisions.

## 📬 Contact Me
- Portfolio: [datascienceportfol.io/shivraj](https://datascienceportfol.io/shivraj)
- GitHub: [github.com/shivrajsinghsisodiya9351-alt](https://github.com/shivrajsinghsisodiya9351-alt)

## 📥 More Details
Want to explore the full model, DAX measures, and interactions yourself? Download the `.pbix` file from the GitHub repo above and open it in Power BI Desktop.
