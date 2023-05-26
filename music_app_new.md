# Music App

## Description

- It is spotify like app, which contains albums, tracks and playlists. 
- Each album should have artist.
- Only authenticated users can able to favourite/unfavourite track.
- Admin panel used to add and manage data by admins
- Website provide a interactive UI for user to use our music app

### Application will have two type of users :

- Admin - Should have Read/Write access
- User - Should have Read access only, except Favourite/Unfavourite functionality

**Note:** Admin is also a user. Admin should have all access same as user. Additionally they can modify the content.

## Models

* Artist
    - id
    - name
    - image_url
    - created_at
    - updated_at

* Album
    - id
    - name
    - description
    - image_url
    - published_at
    - is_published
    - artist_id
    - created_at
    - updated_at

* Track
    - id
    - name
    - index
    - track_url
    - image_url
    - album_id
    - is_published
    - created_at
    - updated_at

* Playlist
    - id
    - name
    - description
    - image_url
    - is_published
    - created_at
    - updated_at

* Favourite-tracks 
    - id
    - track_id
    - user_id
    - index
