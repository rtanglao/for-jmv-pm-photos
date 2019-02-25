# for-jmv-pm-photos
for the fab jmv - photos from pm

## 24February2019 getting the metadata

* To use [get-set-photo-metadata.rb](https://github.com/rtanglao/for-jmv-pm-photos/blob/master/get-set-photo-metadata.rb), first setup mongoddb

```bash
. ./setupFlickrjmvpmDB
```

* and then specify two parameters: the flickr alphanumeric userid and the flickr set id

```bash
./get-set-photo-metadata.rb 36896321@N08 72157622068072145
```
