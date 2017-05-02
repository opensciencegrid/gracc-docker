.PHONY: image
image:
	docker build -t opensciencegrid/gracc-stash-raw:3.2 .
	docker build -t opensciencegrid/gracc-stash-raw:latest .

.PHONY: push
push:
	docker push opensciencegrid/gracc-stash-raw:3.2
	docker push opensciencegrid/gracc-stash-raw:latest
