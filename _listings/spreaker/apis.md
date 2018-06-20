---
name: Spreaker
x-slug: spreaker
description: Discover and listen to your favorite podcasts for free or sign up to
  create your own!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
x-kinRank: "8"
x-alexaRank: "13176"
tags: Spreaker
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/apis.md
specificationVersion: "0.14"
apis:
- name: Spreaker API Get Categories
  x-api-slug: spreaker-api
  description: Retrieves all categories in Spreaker
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////categories/flat
  tags: Categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/categoriesflat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/categoriesflat-get-openapi.md
- name: Spreaker API Change Episode Image
  x-api-slug: spreaker-api
  description: Change Episode Image
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////episode/<episode_id>/image
  tags: Change,Episode,Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-idimage-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-idimage-put-openapi.md
- name: Spreaker API Delete Episode
  x-api-slug: spreaker-api
  description: Deletes an episode. Theres no way to recover a deleted episode.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////episode/{episode_id}
  tags: Episode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-id-delete-openapi.md
- name: Spreaker API Get Episode
  x-api-slug: spreaker-api
  description: Retrieves an episode by unique identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////episode/{episode_id}
  tags: Episode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-id-get-openapi.md
- name: Spreaker API Edit Episode
  x-api-slug: spreaker-api
  description: Edit episode info (eg. title, description, category, tags, ...)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////episode/{episode_id}
  tags: Edit,Episode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-id-put-openapi.md
- name: Spreaker API Get Episode Media List
  x-api-slug: spreaker-api
  description: Get Episode Media List
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////episode/{episode_id}/media
  tags: Episode,Media,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-idmedia-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-idmedia-get-openapi.md
- name: Spreaker API Get Episode Streams
  x-api-slug: spreaker-api
  description: The response contains a collection of ICY streams.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////episode/{episode_id}/streams/icy
  tags: Episode,Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-idstreamsicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-idstreamsicy-get-openapi.md
- name: Spreaker API Get Episode Streams
  x-api-slug: spreaker-api
  description: The response contains a collection of RTMP / RTMPT streams.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////episode/{episode_id}/streams/rtmp
  tags: Episode,Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-idstreamsrtmp-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeepisode-idstreamsrtmp-get-openapi.md
- name: Spreaker API Get Live Episodes
  x-api-slug: spreaker-api
  description: Retrieves all live episodes at the moment of the request
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////episodes/live
  tags: Live,Episodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeslive-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/episodeslive-get-openapi.md
- name: Spreaker API Explore Category Items
  x-api-slug: spreaker-api
  description: 'This API returns information and items of a specific category. The
    response contains two properties at root level:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////explore/{category_id}
  tags: Explore,Category,Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/explorecategory-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/explorecategory-id-get-openapi.md
- name: Spreaker API Create Media
  x-api-slug: spreaker-api
  description: Upload a new Media in the specified user library
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}
  tags: Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-id-post-openapi.md
- name: Spreaker API Get Owned Media
  x-api-slug: spreaker-api
  description: Get a paginated list of media owned by <user_id> filtered by type:.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}/effects/owned
  tags: Owned,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-ideffectsowned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-ideffectsowned-get-openapi.md
- name: Spreaker API Get Owned Media
  x-api-slug: spreaker-api
  description: Get a paginated list of media owned by <user_id> filtered by type:.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}/jingles/owned
  tags: Owned,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-idjinglesowned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-idjinglesowned-get-openapi.md
- name: Spreaker API Get Owned Media
  x-api-slug: spreaker-api
  description: Get a paginated list of media owned by <user_id> filtered by type:.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}/loops/owned
  tags: Owned,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-idloopsowned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-idloopsowned-get-openapi.md
- name: Spreaker API Get Owned Media
  x-api-slug: spreaker-api
  description: Get a paginated list of media owned by <user_id> filtered by type:.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}/songs/owned
  tags: Owned,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-idsongsowned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-idsongsowned-get-openapi.md
- name: Spreaker API Get Owned Media
  x-api-slug: spreaker-api
  description: Get a paginated list of media owned by <user_id> filtered by type:.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}/soundtracks/owned
  tags: Owned,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-idsoundtracksowned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/libraryuser-idsoundtracksowned-get-openapi.md
- name: Spreaker API Get Top Live Episodes
  x-api-slug: spreaker-api
  description: Retrieves live episodes sorted by rank
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////lives/top
  tags: Top,Live,Episodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/livestop-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/livestop-get-openapi.md
- name: Spreaker API Get Media
  x-api-slug: spreaker-api
  description: Retrieves a Media by unique identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////media/{media_id}
  tags: Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/mediamedia-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/mediamedia-id-get-openapi.md
- name: Spreaker API Search users, shows and episodes
  x-api-slug: spreaker-api
  description: Search users, shows and episodes
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////search/{query}
  tags: Search,Users,,Shows,Episodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/searchquery-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/searchquery-get-openapi.md
- name: Spreaker API Search Shows
  x-api-slug: spreaker-api
  description: This API allows to find shows.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////show/search/{query}
  tags: Search,Shows
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showsearchquery-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showsearchquery-get-openapi.md
- name: Spreaker API Dele Show
  x-api-slug: spreaker-api
  description: Deletes a show. Theres no way to recover a deleted show. Only show
    without episodes in it can be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////show/{show_id}
  tags: Dele,Show
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-id-delete-openapi.md
- name: Spreaker API Get Show
  x-api-slug: spreaker-api
  description: Retrieves show information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////show/{show_id}
  tags: Show
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-id-get-openapi.md
- name: Spreaker API Edit Show
  x-api-slug: spreaker-api
  description: Edit show info (name, description and contacts).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////show/{show_id}
  tags: Edit,Show
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-id-put-openapi.md
- name: Spreaker API Get Show Episodes
  x-api-slug: spreaker-api
  description: Retrieves all listenable episodes by show (both live and podcast, ordered
    by published_at DESC).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////show/{show_id}/episodes
  tags: Show,Episodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-idepisodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-idepisodes-get-openapi.md
- name: Spreaker API Create podcast
  x-api-slug: spreaker-api
  description: Creates new podcast episode.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////show/{show_id}/episodes
  tags: Podcast
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-idepisodes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-idepisodes-post-openapi.md
- name: Spreaker API Get All Show Episodes
  x-api-slug: spreaker-api
  description: Retrieves all episodes by show (both live and podcast, ordered by published_at
    DESC).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////show/{show_id}/episodes/all
  tags: Show,Episodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-idepisodesall-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-idepisodesall-get-openapi.md
- name: Spreaker API Create Show
  x-api-slug: spreaker-api
  description: Create a new Show.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////shows
  tags: Show
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/shows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/shows-post-openapi.md
- name: Spreaker API Get List of Followers
  x-api-slug: spreaker-api
  description: Get List of Followers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{followed_id}/fans
  tags: List,Of,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/userfollowed-idfans-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/userfollowed-idfans-get-openapi.md
- name: Spreaker API Follow User
  x-api-slug: spreaker-api
  description: Follow User
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{followed_id}/fans
  tags: Follow,User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/userfollowed-idfans-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/userfollowed-idfans-post-openapi.md
- name: Spreaker API Unfollow User
  x-api-slug: spreaker-api
  description: Unfollow User
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{followed_id}/fans/{follower_id}
  tags: Unfollow,User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/userfollowed-idfansfollower-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/userfollowed-idfansfollower-id-delete-openapi.md
- name: Spreaker API Get List of Following
  x-api-slug: spreaker-api
  description: Get List of Following
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{follower_id}/users/fan
  tags: List,Of,Following
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/userfollower-idusersfan-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/userfollower-idusersfan-get-openapi.md
- name: Spreaker API Get User
  x-api-slug: spreaker-api
  description: Retrieves an user by unique identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}
  tags: User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-id-get-openapi.md
- name: Spreaker API Edit User
  x-api-slug: spreaker-api
  description: Edit user info (eg. fullname, description aka biography, gender, birthday,
    ...).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}
  tags: Edit,User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-id-put-openapi.md
- name: Spreaker API Get User Actions
  x-api-slug: spreaker-api
  description: Retrieves the user actions settings
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/actions
  tags: User,Actions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idactions-get-openapi.md
- name: Spreaker API Facebook Settings
  x-api-slug: spreaker-api
  description: Edit facebook share settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/actions/facebook
  tags: Facebook,Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idactionsfacebook-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idactionsfacebook-get-openapi.md
- name: Spreaker API Twitter Settings
  x-api-slug: spreaker-api
  description: Edit twitter share settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/actions/twitter
  tags: Twitter,Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idactionstwitter-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idactionstwitter-put-openapi.md
- name: Spreaker API Delete Device
  x-api-slug: spreaker-api
  description: Delete the association from a mobile device and a registered user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/device/{token}
  tags: Device
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-iddevicetoken-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-iddevicetoken-delete-openapi.md
- name: Spreaker API Create Device
  x-api-slug: spreaker-api
  description: Creates a new device.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/devices
  tags: Device
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-iddevices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-iddevices-get-openapi.md
- name: Spreaker API Get User Episodes
  x-api-slug: spreaker-api
  description: Retrieves all listenable episodes by user (both live and podcast, ordered
    by published_at DESC).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/episodes
  tags: User,Episodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idepisodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idepisodes-get-openapi.md
- name: Spreaker API Change User Profile Image
  x-api-slug: spreaker-api
  description: Change User Profile Image
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/image
  tags: Change,User,Profile,Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idimage-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idimage-put-openapi.md
- name: Spreaker API Upload An Image
  x-api-slug: spreaker-api
  description: Upload An Image
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/images
  tags: Upload,Image
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idimages-post-openapi.md
- name: Spreaker API Get Favorite Live Episodes
  x-api-slug: spreaker-api
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/lives/fan
  tags: Favorite,Live,Episodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idlivesfan-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idlivesfan-get-openapi.md
- name: Spreaker API Newsfeed
  x-api-slug: spreaker-api
  description: This API returns a list of newsfeed items. The request MUST be authenticated
    (an user can only fetch its own newsfeed).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/newsfeed
  tags: Newsfeed
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idnewsfeed-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idnewsfeed-get-openapi.md
- name: Spreaker API GEt Shows By Author
  x-api-slug: spreaker-api
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/shows/author
  tags: GEt,Shows,Author
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idshowsauthor-get-openapi.md
- name: Spreaker API Get Favorite Shows
  x-api-slug: spreaker-api
  description: Retrieves the list of shows whose authors are followed by <user_id>.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/shows/fan
  tags: Favorite,Shows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/useruser-idshowsfan-get-openapi.md
- name: Spreaker API Search Users
  x-api-slug: spreaker-api
  description: This API allows to find users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////users/search/{query}
  tags: Search,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/userssearchquery-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/userssearchquery-get-openapi.md
- name: Spreaker API Get Authenticated User
  x-api-slug: spreaker-api
  description: Retrieves information about the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////whoami
  tags: Authenticated,User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/whoami-get-openapi.md
- name: Spreaker API Change Show Image
  x-api-slug: spreaker-api
  description: Change Show Image
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com///show/{show_id}/image
  tags: Change,Show,Image
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/showshow-idimage-put-openapi.md
- name: Spreaker API
  x-api-slug: spreaker-api
  description: Spreaker platform enables you to host and listen thousands of radio
    shows. Spreaker provides a REST web service that enables developers to read and
    write data to Spreaker.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com//
  tags: Spreaker
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spreaker/master/_listings/spreaker/openapi.md
x-common:
- type: x-base
  url: http://api.spreaker.com/
- type: x-blog
  url: http://blog.spreaker.com
- type: x-crunchbase
  url: https://crunchbase.com/organization/spreaker
- type: x-crunchbase
  url: http://www.crunchbase.com/company/spreaker
- type: x-developer
  url: http://developers.spreaker.com
- type: x-email
  url: info@spreaker.com
- type: x-email
  url: support@spreaker.com
- type: x-email
  url: advertise@spreaker.com
- type: x-email
  url: tonia.maffeo@spreaker.com
- type: x-email
  url: press@spreaker.com
- type: x-email
  url: legal@Spreaker.com
- type: x-github
  url: https://github.com/spreaker
- type: x-pricing
  url: http://www.spreaker.com/plans
- type: x-twitter
  url: https://twitter.com/spreaker
- type: x-website
  url: http://spreaker.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---