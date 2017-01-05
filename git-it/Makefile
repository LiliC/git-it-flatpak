all:
	cd git-it && npm install && npm run pack-lin

install:
	mkdir -p /app/Gitit
	cp -a git-it/out/Git-it-linux-x64/* /app/Gitit
	ln -s /app/Gitit/Git-it /app/bin/Git-it

.PHONY: all install
