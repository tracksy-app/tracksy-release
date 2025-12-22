## [0.3.1] - 2025-12-22

### 🚀 Features

- Start on the simple view
- *(dependabot)* Add gitsubmodule updates configuration for blog dependencies
- Rename ExpertView to DetailedView
- Setup moon
- Add support for hugo blog

### 🐛 Bug Fixes

- Define default pull request template
- Fetch repo before moon

### 🚜 Refactor

- Rename StreamPerMonth return type and query name
- Rename StreamPerHour return type and query name
- Rename SummaryPerYear return type and query name
- Rename TopTracks return type and query name
- Rename TopArtists return type and query name
- Rename summarizeQuery return type and query name
- Handle queryTop10Evolution and streamPerDayOfWeekQueryByYear
- Rename Charts to ExpertView
- Move expert chart features to a specific folder
- Move summarize feature to a specific folder

### 📚 Documentation

- Add testing best practices to CONTRIBUTING.md
- Update CONTRIBUTING.md with Testing Best Practices
- Introduce ADRs
- Tooling for Monorepo Management

### 🎨 Styling

- Review the overall style

### 🧪 Testing

- Remove components mocks from ExpertView tests
- Remove vi.mock from TracksyWrapper tests
- Fix flaky test by adding secondary platform sort
- Remove vi.mock from FunFacts tests
- Remove vi.mock from ListeningRhythm tests
- Remove vi.mock from SeasonalPatterns tests
- Remove vi.mock from StreamPerHour tests
- Remove vi.mock from StreamPerMonth tests
- Remove vi.mock from SummaryPerYear tests
- Remove vi.mock from TopArtist tests
- Remove vi.mock from TopArtists tests
- Remove vi.mock from TopStreak tests
- Remove vi.mock from TopTracks tests
- Remove vi.mock from TotalStreams tests
- Remove vi.mock from StreamPerDayOfWeek tests
- Remove vi.mock from Results tests
- Fix flaky tests due to test preparation

### ⚙️ Miscellaneous Tasks

- Disable eslint rule on default export
- Add ESLint rule to restrict mocks
- Run tests on main branch
- Adapt CH actions to use moon
- *(release)* V0.3.1
