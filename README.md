Author: Rodrigo Monteiro Junior [rodrigo.monteiro.tech@gmail.com]


## Import go module if it's not imported already

	1/import/;/)/ v/"<mod>"/ -+ a/\t"<mod>"\n

	NOTE: if you wish to add the import at the bottom,
	substitute '-+ a' for '+- i'.


## Add prefix to the first match of `pat2` in every line containing `pat`

	, x/<pat>/ -+ /<pat2>/ i/<prefix>/
