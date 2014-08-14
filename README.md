newrelic-deployment
===================

Send a deploy event to NewRelic


Example
--------

Add NEWRELIC_API_KEY as deploy target or application environment variable.

```
    - mactynow/newrelic-deployment:
        api_key: $NEWRELIC_API_KEY
        app_name: MyApp
        revision: **OPTIONAL** // default: '$WERCKER_GIT_BRANCH/$WERCKER_GIT_COMMIT by $WERCKER_STARTED_BY'
```
