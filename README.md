# Tagesschau-API
Documentation for APH's Tagesschau API

## Endpoints
| Name     | Description                                                                    | URL            |
|----------|--------------------------------------------------------------------------------|----------------|
| news     | The latest 40 Articles published on the Tagesschau Website                     | /news          |
| article | Response with an Article depending on what Value you pass along with it (0-39) | /news/article |

## Open Endpoints
Open endpoints require no Authentication.
* News : `GET /news`
* Article: `GET /news/article/<INT 0-39>`
