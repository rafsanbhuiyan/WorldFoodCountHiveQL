

SELECT area abbreviation, area code, area,  item code, item,
	element code, element unit, latitude, longitude, y2011, y2012, y2013
	from hivetable WHERE area = "United States of America";
	

SELECT DISTINCT item FROM hivetable WHERE area = "United States of America";

SELECT area, COUNT(item) AS itemCount FROM hivetable GROUP BY area;