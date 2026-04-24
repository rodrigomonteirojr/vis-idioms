Author: Rodrigo Monteiro Junior [rodrigo.monteiro.tech@gmail.com]

CREATION is supposed to be some time around 20-04-2026, my filesystem
has no creation date!

## Import go module if it's not imported already

v1 - CREATION:

	1/import/;/)/ v/"<mod>"/ x/import/ +- a/\t"<mod>"\n/

v2 - Fri Apr 24 12:36:49 -03 2026 (rodrigo.monteiro.tech@gmail.com):

	1/import/;/)/ v/"<mod>"/ -+ a/\t"<mod>"\n

	NOTE: if you wish to add the import at the bottom,
	substitute '-+ a' for '+- i'.


## Add prefix to the first match of <pat2> in every line containing <pat>

~~Add prefix to the every match of <pat2> in every line containing <pat>~~

v1 - CREATION:

	, x/<pat>/ +- x/<pat2>/ i/<prefix>/

v2 - Fri Apr 24 12:52:41 -03 2026:

	, x/<pat>/ -+ /<pat2>/ i/<prefix>/

	IMPROVEMENTS: matches only once each line,
	avoiding problems with multiple ocurrences of the
	pattern. This fits my usage more specifically, so i also
	altered the title.

# vis-idioms
