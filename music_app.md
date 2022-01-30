# Music App

## Description

* Create a project that will enable admin or end-users to register and login to the app and can manage below data with golang and MYSQL(Recommended : gin framework).

* There will be two types of authentications
    - Admin - will have read and write access to data
    - user - will only have read access to data (except favourite/unfavourite tracks feature)

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


## APIs for admin authentication

* Admin Register
* Admin Login

## APIs for user authentication

* User Register
* User Login

## APIs for admin functionalities
* Create/Read/Update/Delete artist
* Create/Read/Update/Delete album
* Create/Read/Update/Delete track
* Add tracks to album
* Remove tracks from album
* Create/Read/Update/Delete playlist
* Add tracks to playlist
* Remove tracks from playlist
* Get playlists
* Get playlist and tracks by playlist id

## APIs for user functionalities
* Fetch all albums
* Fetch all tracks
* Fetch all tracks by album Id
* Get playlists
* Get playlist and tracks by playlist id
* Favourite/unfavourite tracks
* Retrieve favourite/unfavourite tracks of own
