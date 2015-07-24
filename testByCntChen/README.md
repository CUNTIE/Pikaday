# Update #

## Set default format without moment.js ##

*Usage:*

> 		var picker = new Pikaday({
			field: document.getElementById('datepicker'),
			format: 'YYYY/MM/DD'
		});

Use `format` to defind return date format

* **keywords:** `Y` for **Year**, `M` for **Month**, `D` for **Date**

* **separate:** `/` `-`

* the order of `Y` `M` `D` deside the order of output format

* the number of **keywords** , **separate** are same
    
    	YYYY == YY == Y

* lowcase and largecase are all OK

## Edit input and update Pikaday syc ##

Use **input** `onkeyup` event to listen input text change and update **Pikaday** div

## Input `Enter` to finish date picker and hide Pikady ##

`keyup` of *enter* keyboard to finish date picker

## TODO ##

* Check input text format

* support other setting
> Hour:minute:second:millisecond:time zome 