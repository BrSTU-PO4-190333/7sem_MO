docker-compose-script:
	cd /app/report

	latexmk -pdf -output-directory=/temp/ -jobname=MO.PO4.190333-00_81_00 main.tex
	
	cp /temp/*.pdf /build/
