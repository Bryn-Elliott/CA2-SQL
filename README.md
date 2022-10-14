Ella's Branch

CA2 SQL Assessment
Group i

Members:
Ella Thomson
Theo Musa
Jonathon Love
Rhys spears
Bryn Elliott

SELECT TrackId FROM 'playlist_track' WHERE PlaylistId = (SELECT PlaylistId FROM 'playlists' WHERE Name = "Grunge") EXCEPT SELECT TrackId FROM 'invoice_items'
