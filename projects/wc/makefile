cs:
	@echo `pwd`
	@rsync -r -t -u -v --delete \
	--include "*.html"          \
	--include "*.xml"           \
	--include "*.xsd"           \
	--exclude "*"               \
	. downing@$(CS):cs/projects/wc/
