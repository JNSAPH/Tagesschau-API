# Tagesschau-API
Documentation for APH's Tagesschau API

## Endpoints
| Name     | Description                                                                    | URL            |
|----------|--------------------------------------------------------------------------------|----------------|
| news     | The latest 40 Articles published on the Tagesschau Website                     | /news          |
| articles | Response with an Article depending on what Value you pass along with it (0-39) | /news/articles |

## Open Endpoints
Open endpoints require no Authentication.
* News : `GET /news`
* Articles: `GET /news/articles/<INT 0-39>`
