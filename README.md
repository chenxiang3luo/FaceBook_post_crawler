# FaceBook_post_crawler
: get the post and repost of some topic on FaceBook

**fb.ipynb**
: get the information of posts and reposts under specific topic

**fillter_empty.ipynb**
filltered some posts with little reposts

**get_labels.ipynb**
: add the attribute 'label' for further labeling

**get_trees.ipynb**
: get the tree structure of posts and reposts

**get_uuid**
: set uuid for every posts and reposts

### data format
```
{"post_url": "https://www.facebook.com/permalink.php", "post_time": "2023年03月01日", "post_user_url": "https://www.facebook.com/profile.php", "post_user_name": "xxxx", "post_text": "xxxx", "post_reaction_num": "40", "post_share_comment": "2条评论\n8次分享", "reposts": [{"post_text": xxx, "post_reaction_num": "4", "post_share_comment": "2", "post_url": "xxx", "post_time": "2023年03月02日", "post_user_url": "xxx", "post_user_name": "xxx", "parent_url": "xxxx", "reposts": []},...{}]
```
