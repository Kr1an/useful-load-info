## Useful load info
repository contains info used in
- useful load chrome extension

structure to this repository is as follows:
- file topics.json contains the keys equal to number of topic and value equal to the path of the file, which contains topic's data
- each topic file is named <topic>.json. It contains an array of string

So, information is extensible. To add a new topic, modify topics.json and then create corresponding json file describing previously added topic
If topic exist in topics.json but no topic's file found, it equivalent to the topic that has emply array as info. By design, there should not be undefined topics
