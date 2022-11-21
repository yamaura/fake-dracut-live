.PHONY:all srpm

all: srpm

srpm:
	rpmbuild -bs ../dracut-live.spec --define "_sourcedir $(PWD)" --define "_srcrpmdir $(outdir)"
