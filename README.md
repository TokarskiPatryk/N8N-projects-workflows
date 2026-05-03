You can probably find each project here: https://tokarskipatryk.github.io/projects/


# Radio tracks to Spotify
This folder contains N8N workflow `.json` files that scrape currently playing tracks from selected online radio stations and add them to Spotify playlists. Playlists are cleared daily and repopulated; workflows add new tracks periodically throughout the day.

For Radio Kampus there are two complementary workflows:
- `Radio_Kampus_Today.json` — adds currently playing tracks live during the day.
- `Radio_Kampus_Yesterday.json` — updated at midnight; contains a consolidated list of all tracks played on the previous day.

Other available workflows:
- Q-Music channel (Dutch) (thanks to [g4ntel](https://github.com/g4ntel))
- Studio Brussel (Belgian) (thanks to [g4ntel](https://github.com/g4ntel))
For Radio Kampus there are two complementary workflows:
- `Radio_Kampus_Today.json` — dodaje bieżące utwory na żywo przez cały dzień.
- `Radio_Kampus_Yesterday.json` — uruchamiany/aktualizowany o północy; zawiera zbiór wszystkich piosenek z dnia poprzedniego.

Pozostałe dostępne workflowy:
- Q-Music channel (Dutch) (thanks to [g4ntel](https://github.com/g4ntel))
- Studio Brussel (Belgian) (thanks to [g4ntel](https://github.com/g4ntel))

## Lubelski Rower Miejski
The `Lubelski Rower Miejski.json` workflow is used to scrape data about the city bike system in Lublin and upload it to a target website or service. The workflow collects relevant information (e.g., station status and bike availability) and prepares the dataset for publication.