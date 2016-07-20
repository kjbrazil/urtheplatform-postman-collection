# UrthePlatform Postman Collection

A set of example HTTP requests for the UrthePlatform APIs using Postman. These include:

* Archive
* Areas of Interest
* Events
* Satellite Tracker

# Requirements

In order to utilize this repo you will need two things:

1. An [UrthePlatform account](https://developers.urthecast.com/apps).
2. [Postman](https://www.getpostman.com) for Mac or Chrome.

# Setup

1. Clone or download this repo to your local machine.
2. Open Postman.
3. In the top left corner click "Import".
4. Click "Import Folder".
5. Drag or find your ``urtheplatform-postman-collection`` folder and click open.
6. Both the collection and the environment variables will be imported to Postman.
7. In the top right corner to the left of the eye icon, click the drop down and select "Manage Environments".
8. Click "UrtheCast".
9. Navigate to your [UrthePlatform apps page](https://developers.urthecast.com/apps) to obtain your key & secret.
10. Navigate back to Postman and replace ``your_api_key`` and ``your_api_secret`` with your actual credentials.
11. Click "Update" and close the window.
12. Click the environment drop down again and select "UrtheCast".
13. You are now ready to start making API calls!
14. Try querying all scenes by clicking the Archive folder > "Query All Scenes" > Send.

# Support

If you encounter any issues please [create an issue](https://github.com/kjbrazil/urtheplatform-postman-collection/issues/new). Please also feel free to improve upon the collection and submit pull requests. :-)
