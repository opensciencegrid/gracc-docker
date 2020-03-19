.PHONY: image
image:
	docker build -t opensciencegrid/gracc-stash-summary:3.5-transfer .
	docker build -t opensciencegrid/gracc-stash-summary:transfer .

.PHONY: push
push:
	docker push opensciencegrid/gracc-stash-summary:3.5-transfer
	docker push opensciencegrid/gracc-stash-summary:transfer
