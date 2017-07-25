mkfile_path := $(shell dirname $(realpath $(lastword $(MAKEFILE_LIST))))

#dev
dev: 
	./run_attacks_and_defenses_dev.sh dev $(mkfile_path)/tmp

clean:
	rm -r $(mkfile_path)/tmp/*

#sample
sample:
	./run_attacks_and_defenses_dev.sh sample

