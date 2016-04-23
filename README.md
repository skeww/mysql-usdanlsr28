# mysql-usdanlsr28
MySql scripts to generate the USDA National Nutrient Database, version SR 28

#EXPLANATION
The USDA National Nutrient Database for Standard Reference is a publicly available data set. ASCII Files are available here: http://www.ars.usda.gov/Services/docs.htm?docid=8964

The sql files in this repository are generated from these files.
The schema was created by https://github.com/nmaster, available here https://github.com/nmaster/usdanl-sr28-mysql
I wasn't able to use the shell script provided, as I'm not running Ubuntu, so I ended up generating these sql files an importing them instead. 

It took a bit of time just to generate them, so I hope that this repo will save someone else that time.

#INSTALLATION
Just run create.sql first, constraints.sql last, and the rest of the scripts in any order.
