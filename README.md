# standard_objects
Models of standard YCB objects used in RoboCup@Home

[List of RoboCup@Home standard objects](https://github.com/RoboCupAtHome/AtHomeCommunityWiki/wiki/Standard-Objects)

The object meshes are downloaded from sources online, and configured to be used in the Gazebo simulator. 
Some meshes are bad collision models and they are replaced by simple meshes such as box and cylinder.

## Models included in this package

| YCB ID | YCB Name | @home Name | Collision Model | Visual Model |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| 1 | chips can | chips | cylinder | [link](https://github.com/eleramp/ycb-objects-models-sim/tree/master/ycb_objects_models_sim/objects/YcbChipsCan) |
| 2 | master chef can | coffee | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/002_master_chef_can_google_16k.tgz) | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/002_master_chef_can_google_16k.tgz) |
| 3 | cracker box | cracker | box | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/003_cracker_box_google_16k.tgz) |
| 4 | sugar box | sugar | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/004_sugar_box_google_16k.tgz) | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/004_sugar_box_google_16k.tgz) |
| 5 | tomato soup can | tomato soup | cylinder | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/005_tomato_soup_can_google_16k.tgz) |
| 6 | mustard bottle | mustard | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/006_mustard_bottle_google_16k.tgz) | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/006_mustard_bottle_google_16k.tgz) |
| 7 | tuna fish can | tuna | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/007_tuna_fish_can_google_16k.tgz) | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/007_tuna_fish_can_google_16k.tgz) |
| 8 | pudding box | pudding | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/008_pudding_box_google_16k.tgz) | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/008_pudding_box_google_16k.tgz) |
| 9 | gelatin box | jello | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/009_gelatin_box_google_16k.tgz) | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/009_gelatin_box_google_16k.tgz) |
| 10 | potted meat can | potted meat | box with rounded edges | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/010_potted_meat_can_google_16k.tgz) |
| 19 | pitcher base | pitcher | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/019_pitcher_base_google_16k.tgz) | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/019_pitcher_base_google_16k.tgz) |
| 21 | bleach cleanser | bleach | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/021_bleach_cleanser_google_16k.tgz) | [google 16k](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/021_bleach_cleanser_google_16k.tgz) |
| 22 | windex bottle | windex | [google 16k<sup>1</sup>](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/022_windex_bottle_google_16k.tgz) | [google 16k<sup>1</sup>](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/data/google/022_windex_bottle_google_16k.tgz) |

<sup>1</sup> The meshes are incomplete and the object cannot be simulated well.
