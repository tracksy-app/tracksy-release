## [0.3.0] - 2025-12-05

### 🚀 Features

- Generate more rows for the demo
- Filter out non-music streams
- *(ui)* Add light/dark mode toggle with system preference support (#141)
- Inform the user that the database is being prepared
- Put charts on card
- Make the legend easier to read
- Add the number of streams to the tooltip
- Freeze the scale between years
- Add chart title
- *(StreamPerHour)* Add duration to the tooltip
- *(Charts)* Add TopTracks chart
- *(HowToButton)* Inform user how to download data
- *(Charts)* Add TopArtists chart
- Add streaks chart
- Add top10 evolution
- Separate charts under development from the rest
- Add TopStreak
- Add TotalStreams
- Add TopArtist
- Only keep streams that are at least 30 seconds long
- Add stream per day of week and hour
- Refine categories of stream distribution
- Create simple view components
- Add duration to evolution chart
- Returns number with language-sensitive representation
- Render simple view by year

### 🐛 Bug Fixes

- *(Dropzone.tsx)* Improve label by specifying which data
- View StreamPerMonth per month

### 📚 Documentation

- Fix ci labels
- *(SECURITY.md)* Initial security policy
- Add development guide with Spotify setup instructions
- Update the readme with the new ui

### 🎨 Styling

- Format SQL query
- Improve readability

### 🧪 Testing

- Mock queryDB to return Apache Arrow Table
- Fix DropZoneWrapper prop

### ⚙️ Miscellaneous Tasks

- Remove the dependency the dependency that does not change from useEffect
- Reduce abstraction
- Reduce plot recomputation
- Remove useless react import
- Use json instead of arrow
- Use band instead of utc
- Use double instead of integer
- *(lint)* Add isort rules
