.PHONY: clone-trie
clone-trie:
	git clone -b empty-remove-bug https://github.com/derekparker/trie

.PHONY: test
test:
	GO111MODULE=off go test -v ./trie

.PHONY: debug
debug:
	GO111MODULE=off cd ./trie && dlv debug

.PHONY: dlv-test
dlv-test:
	GO111MODULE=off cd ./trie && dlv test