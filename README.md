

CA2 SQL Assessment
Group i

Members:
Ella Thomson
Theo Musa
Jonathan Love
Rhys Speers
Bryn Elliott

SELECT TrackId FROM 'playlist_track' WHERE PlaylistId = (SELECT PlaylistId FROM 'playlists' WHERE Name = "Grunge") EXCEPT SELECT TrackId FROM 'invoice_items'

SELECT STRFTIME('%d-%m-%Y', HireDate) FROM 'employees'
