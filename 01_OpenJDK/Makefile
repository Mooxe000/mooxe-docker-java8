pjName := mooxe/openjdk

build:
	docker build -t ${pjName} .

rebuild:
	docker build --no-cache=true -t ${pjName} .

in:
	docker run --rm --name=mooxe_sdkman -t -i ${pjName} /bin/bash

push:
	docker push ${pjName}
