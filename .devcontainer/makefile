.PHONY: build_fast build update rebuild clean

build_fast:
	python3 .devcontainer/build.py
build:
	rm -rf /workspaces/work/build
	python3 .devcontainer/build.py
update:
	rm -rf /workspaces/work/build
	python3 .devcontainer/build.py --update
clean:
	rm -rf /workspaces/work
	rm -rf release