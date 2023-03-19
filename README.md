# python-cli-mysql-to-multi-node-elasticsearch-client-without-ssl-simple

## Description
Reads a multi node cluster for data in `animal-demo` document.

Uses `dog` table then covverts it to json for
elasticsearch to use.

## Tech stack
- python
    - pymysql
    - sqlalchemy
- elasticsearch
- kibana
- mysql

## Docker stack
- python
- elasticsearch
- kibana
- mariadb

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Docker setup](https://lynn-kwong.medium.com/all-you-need-to-know-about-using-elasticsearch-in-python-b9ed00e0fdf0)
- [Search setup](https://www.elastic.co/guide/en/elasticsearch/client/python-api/master/examples.html)