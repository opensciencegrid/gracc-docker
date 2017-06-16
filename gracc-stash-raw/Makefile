.PHONY: image
image:
	docker build -t opensciencegrid/gracc-stash-raw:3.3 .
	docker build -t opensciencegrid/gracc-stash-raw:latest .

.PHONY: push
push:
	docker push opensciencegrid/gracc-stash-raw:3.3
	docker push opensciencegrid/gracc-stash-raw:latest
