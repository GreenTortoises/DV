## Pre-reqs

Docker desktop - [Link](https://www.docker.com/products/docker-desktop)

Get your licence from [Link](https://community.denodo.com/express/) and place it into licence folder

Download the denodo express binary and place into root folder

## Dataset

Download dataset from [Link](https://www3.stats.govt.nz/2018census/Age-sex-by-ethnic-group-grouped-total-responses-census-usually-resident-population-counts-2006-2013-2018-Censuses-RC-TA-SA2-DHB.zip)

## To get started

Run `docker build -t denodo .` to build the denodo image locally

Run `docker-compose up` and this will bring up Deonodo, Spark & Postgres

To access Denodo VDP - you will need to install the denodo in your local machine. Head to your denodo install folder and run bin/vdpadmin.sh