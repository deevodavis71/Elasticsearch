Taken from originally (including concpect, scripts etc)
=======================================================

https://stefanprodan.com/2016/elasticsearch-cluster-with-docker/

./up.sh
./down.sh


Install Elasticsearch HQ
========================

git clone https://github.com/ElasticHQ/elasticsearch-HQ.git

docker build -t es-hq .


Running Elasticsearch HQ
========================

docker run -it -p 5000:5000 --network es-net es-hq


Using Elasticsearch HQ
======================

http://es-t0:9200


Elasticsearch 101
=================

http://joelabrahamsson.com/elasticsearch-101/
