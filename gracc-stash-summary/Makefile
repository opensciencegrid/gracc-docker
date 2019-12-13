.PHONY: image
image:
	docker build -t opensciencegrid/gracc-stash-summary:3.5 .
	docker build -t opensciencegrid/gracc-stash-summary:latest .

.PHONY: push
push:
	docker push opensciencegrid/gracc-stash-summary:3.5
	docker push opensciencegrid/gracc-stash-summary:latest
