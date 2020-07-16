# Recommender-System-and-AI

## IDEA OF PROGRAM
The idea is to build a recommender system based on these datasets to give some suggestions to the users. And then find the similarities between posts.
I used the two types:
Content Based Filtering: Recommend posts for the given user
Collaborative Filtering: Recommend similar posts for the given post

## Dataset Details
### There are 3 files.
1. Users dataset containing user's details like name, id, gender etc (users.csv)
2. Post dataset containing posts details like title category etc. (posts.csv)
3. Views dataset contains the mapping which user views which post(s). (views.csv)

## Users
* _id: a unique alphanumeric id of the user (string)
* name: Name of user (string)
* gender: Gender of user (male | female)
* academics: Education of the use (undergraduate | graduate)

## Posts
* _id: a unique alphanumeric id of the post (string)
* title: Title of the post (string)
* category: Category of the post (string)
* post_type: Type of the post (blog | artwork | skill | project)

## Views
* user_id : a unique alphanumeric id of the user (string)
* post_id : a unique alphanumeric id of the post (string)
* time stamp: timestamp of when user viewed the post (ISO time format)
