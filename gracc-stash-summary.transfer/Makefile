.PHONY: image
image:
	docker build -t opensciencegrid/gracc-stash-summary:3.2-transfer .
	docker build -t opensciencegrid/gracc-stash-summary:transfer .

.PHONY: push
push:
	docker push opensciencegrid/gracc-stash-summary:3.2-transfer
	docker push opensciencegrid/gracc-stash-summary:transfer
