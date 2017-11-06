# servicenow-video-widget
ServiceNow Widget for Video using HTML5

This widget allows the displaying of videos in Service Portal. For external videos, the url can be supplied (please note that YouTube videos may not work correctly due to security / white listing settings - investigation is required to get this working), or the query can be supplied to retrieve a video from the db_video table.

### Options

Either the "source" or "query" options need to be supplied.

* source - URL of video
* query - Query to retrieve a video from the db_video table.
* type - MIME type of video. This is optional.