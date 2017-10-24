# dss-sql-workshop

presented by nicole chen and ricky pan as part of the workshop series brought together by data science society at berkeley
slides can be found here: http://bit.ly/2h3qcJh

## environment set-up
0. download sqlite studio (https://sqlitestudio.pl/index.rvt?act=download)
1. download and import cereal.db into sqlite studio


## cereal.db schemas
#### info
name | mfr | type | shelf | rating
--- | --- | --- | --- | ---
name of cereal | manufacturer of cereal | cold or hot | display shelf (1, 2, 3 counting from floor) | rating of cereal

#### nutrition
name | calories | protein | fat | sodium | fiber | carbo | sugars | potass | vitamins
--- | --- | --- | --- | --- | --- | --- | --- | --- | ---
name of cereal | calories per serving | grams of protein | grams of fat | milligrams of sodium | grams of dietary fiber | grams of complex carbohydrates | grams of sugars | milligrams of potassium | vitamins and minerals - 0, 25, or 100, indicating the typical percentage of FDA recommended


#### serving
name | weight | cups
--- | --- | ---
name of cereal | weight in ounces of one serving | number of cups in one serving


## mini-project
once you have your csv, head here to make some cool visualizations http://evanplaice.github.io/jquery-csv/examples/google-visualization.html


## feedback form
[put link here]


## acknowledgements
thanks to kaggle for the cereal data (https://www.kaggle.com/crawford/80-cereals) and evanplaice for the jQuery-CSV + Google Visualization API
