# Data Dictionary

| #  | Column                                          | Type   | Description |
|----|-------------------------------------------------|--------|-------------|
| 1  | annotation_count                                | int    | Number of lyric annotations contributed by users. |
| 2  | api_path                                        | object | API endpoint path to access detailed song info. |
| 3  | artist_names                                    | object | Names of artists involved in the song (string). |
| 4  | full_title                                      | object | Full title of the song (including artist names). |
| 5  | header_image_thumbnail_url                      | object | URL of the song’s header thumbnail image. |
| 6  | header_image_url                                | object | URL of the main header image for the song. |
| 7  | id                                              | int    | Unique ID of the song in Genius. |
| 8  | lyrics_owner_id                                 | int    | ID of the user who owns the lyrics. |
| 9  | lyrics_state                                    | object | Lyrics status (e.g. complete, in-progress). |
| 10 | path                                            | object | Relative path to the song page. |
| 11 | primary_artist_names                            | object | Name of the primary artist(s). |
| 12 | pyongs_count                                    | float  | Number of “Pyongs” (likes/upvotes) on Genius. |
| 13 | relationships_index_url                         | object | URL of the relationships index page. |
| 14 | release_date_for_display                        | object | Display release date (string format). |
| 15 | release_date_with_abbreviated_month_for_display | object | Release date with abbreviated month (string). |
| 16 | song_art_image_thumbnail_url                    | object | URL of the song’s cover art thumbnail. |
| 17 | song_art_image_url                              | object | URL of the main song cover art. |
| 18 | title                                           | object | Song title. |
| 19 | title_with_featured                             | object | Song title including featured artists. |
| 20 | url                                             | object | Genius URL of the song. |
| 21 | featured_artists                                | object | List of featured artists (JSON/dict structure). |
| 22 | primary_artists                                 | object | Primary artist details (JSON/dict structure). |
| 23 | release_date_components.year                    | float  | Year of release. |
| 24 | release_date_components.month                   | float  | Month of release. |
| 25 | release_date_components.day                     | float  | Day of release. |
| 26 | stats.unreviewed_annotations                    | int    | Number of unreviewed annotations. |
| 27 | stats.hot                                       | bool   | Whether the song is trending/hot. |
| 28 | stats.pageviews                                 | float  | Total pageviews of the song. |
| 29 | primary_artist.api_path                         | object | API path for the primary artist. |
| 30 | primary_artist.header_image_url                 | object | Header image URL of the primary artist. |
| 31 | primary_artist.id                               | int    | Unique ID of the primary artist. |
| 32 | primary_artist.image_url                        | object | Profile image URL of the primary artist. |
| 33 | primary_artist.is_meme_verified                 | bool   | Whether the artist is meme-verified. |
| 34 | primary_artist.is_verified                      | bool   | Whether the artist is officially verified. |
| 35 | primary_artist.name                             | object | Name of the primary artist. |
| 36 | primary_artist.url                              | object | Genius profile URL of the primary artist. |
| 37 | primary_artist.iq                               | float  | IQ score of the artist (reputation metric on Genius). |
| 38 | release_date_components                         | float  | Null or missing release date info. |
| 39 | stats.concurrents                               | float  | Number of concurrent listeners (real-time). |
| 40 | featured_artists_id                             | float  | ID of the featured artist. |
| 41 | featured_artists_name                           | object | Name of the featured artist. |
| 42 | featured_artists_image_url                      | object | Profile image URL of the featured artist. |
