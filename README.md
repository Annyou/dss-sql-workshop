# dss-sql-workshop

presented by nicole chen and ricky pan as part of the data science workshop series brought together by data science society at berkeley

## pre-workshop
0. rsvp at http://bit.ly/2h3RFuH
1. follow event updates at http://bit.ly/2h3SrYD
2. if you'd like, set up your environment by following sqliteSetup.pdf

## slides
0. without solution: http://bit.ly/2h3qcJh
1. solution slides: to be posted after the workshop

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
https://goo.gl/forms/ySMEiNf7FEcLFWOi2

## acknowledgements
thanks to kaggle for the cereal data (https://www.kaggle.com/crawford/80-cereals) and evanplaice for the jQuery-CSV + Google Visualization API
