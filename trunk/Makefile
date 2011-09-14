doc: FORCE
	cd ./lib/jsdoc-toolkit/ && ./jsrun.sh -t=templates/jsdoc -d=./../../doc ./../../src/
	
dist: FORCE
	rm -r -f ./dist
	mkdir dist
	mkdir dist/doc dist/src dist/tests
	cp -r doc/* dist/doc
	cp -r src/* dist/src
	cp -r tests/* dist/tests
	cp CHANGELOG README LICENSE dist/
	cd dist && tar -czvf ../javascript-yaml-parser.tar.gz *
	rm -r -f dist
	
FORCE:
