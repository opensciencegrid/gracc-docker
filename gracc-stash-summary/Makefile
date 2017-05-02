.PHONY: image
image:
	docker build -t opensciencegrid/gracc-stash-summary:3.1 .
	docker build -t opensciencegrid/gracc-stash-summary:latest .

.PHONY: push
push:
	docker push opensciencegrid/gracc-stash-summary:3.1
	docker push opensciencegrid/gracc-stash-summary:latest
