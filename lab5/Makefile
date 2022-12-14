all: drawio tex

tex:
	docker-compose -f docker-compose.tex.yml up
	docker-compose -f docker-compose.tex.yml down

tex-down:
	docker-compose -f docker-compose.tex.yml down

drawio:
	docker-compose -f docker-compose.drawio.yml up
	docker-compose -f docker-compose.drawio.yml down

drawio-down:
	docker-compose -f docker-compose.drawio.yml down
