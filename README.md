# flickr_lite

### This is an demo project with the basic functionalities like authentication, pagination, filtering and user_level data protection.

### Download steps:
#### 1. Download the zip file, load the files, activate the env within the project and run the application.
#### 2. Your own env can be created to run the application by using the requiremnets.txt file.

### Project Design
#### The project is to simulate the basic functionality of Filckr app, here the sqlite db consists of three users created and there are many groups under each user and many more images under each group. 
#### Here the images are coupled with groups and users and hence a user cannot access the images associated with other user.
#### Since there is only one version, the basic way of versioning is done by defining base url's.

### Test data
#### user 1, user_name: sujith, password: 11111111
#### user 2, user_name: sunny, passowrd: 11111111

#### Using chrome browser is recomonded.

### Urls
#### To_login: http://127.0.0.1:8000/v1/
#### list-groups: http://127.0.0.1:8000/v1/groups/
#### Group_detail: http://127.0.0.1:8000/v1/groups/7/
#### List-images: http://127.0.0.1:8000/v1/images/
#### image-detail: http://127.0.0.1:8000/v1/images/41/
#### click on field 'image_url' to open the image.
