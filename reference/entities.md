# Entities

Dive into the specifics of each API endpoint by checking out our complete documentation.

## Genres

This entity contains most of the common music genres with the following properties.

<pre><code><strong>id SERIAL Primary Key
</strong><strong>name String
</strong></code></pre>

## Subgenres

Everything related to subgenres with the following properties

```
id SERIAL Primary Key
name String
genre_id Integer Foreign Key
```

## Artists

Everything related to artists with the following properties

```
id SERIAL Primary Key
name String
genre_id Integer Foreign Key
```

## Albums

Everything related to albums with the following properties

```
id SERIAL Primary Key
name String
artist_id Integer Foreign Key 
genre_id Integer Foreign Key
```

## Sons

Everything related to songs with the following properties

```
id SERIAL Primary Key
name String
album_id Integer Foreign Key
artist_id Integer Foreign Key
genre_id Integer Foreign Key
```
