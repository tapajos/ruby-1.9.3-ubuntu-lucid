# installing

## amd64

	sudo -i
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/amd64/libffi5_3.0.9-1_amd64.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/amd64/libruby1.9.1_1.9.3.0-1_amd64.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/amd64/ruby1.9.1_1.9.3.0-1_amd64.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/amd64/libruby1.9.1-dbg_1.9.3.0-1_amd64.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/amd64/ruby1.9.1-dev_1.9.3.0-1_amd64.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/amd64/ri1.9.1_1.9.3.0-1_all.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/amd64/ruby1.9.1-examples_1.9.3.0-1_all.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/amd64/ruby1.9.1-full_1.9.3.0-1_all.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/amd64/ruby1.9.3_1.9.3.0-1_all.deb
	dpkg -i libffi5_3.0.9-1_amd64.deb libruby1.9.1_1.9.3.0-1_amd64.deb ruby1.9.1_1.9.3.0-1_amd64.deb libruby1.9.1-dbg_1.9.3.0-1_amd64.deb ruby1.9.1-dev_1.9.3.0-1_amd64.deb ri1.9.1_1.9.3.0-1_all.deb ruby1.9.1-examples_1.9.3.0-1_all.deb ruby1.9.1-full_1.9.3.0-1_all.deb ruby1.9.3_1.9.3.0-1_all.deb
	# ignore some errors and run the lines below
	apt-get -f install
	dpkg -i libffi5_3.0.9-1_amd64.deb libruby1.9.1_1.9.3.0-1_amd64.deb ruby1.9.1_1.9.3.0-1_amd64.deb libruby1.9.1-dbg_1.9.3.0-1_amd64.deb ruby1.9.1-dev_1.9.3.0-1_amd64.deb ri1.9.1_1.9.3.0-1_all.deb ruby1.9.1-examples_1.9.3.0-1_all.deb ruby1.9.1-full_1.9.3.0-1_all.deb ruby1.9.3_1.9.3.0-1_all.deb

## i386

	sudo -i
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/i386/libffi5_3.0.9-1_i386.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/i386/libruby1.9.1-dbg_1.9.3.0-1_i386.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/i386/libruby1.9.1_1.9.3.0-1_i386.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/i386/libtcltk-ruby1.9.1_1.9.3.0-1_i386.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/i386/ri1.9.1_1.9.3.0-1_all.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/i386/ruby1.9.1-dev_1.9.3.0-1_i386.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/i386/ruby1.9.1-examples_1.9.3.0-1_all.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/i386/ruby1.9.1-full_1.9.3.0-1_all.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/i386/ruby1.9.1_1.9.3.0-1_i386.deb
	wget https://github.com/tapajos/ruby-1.9.3-ubuntu-lucid/raw/master/i386/ruby1.9.3_1.9.3.0-1_all.deb
	dpkg -i libffi5_3.0.9-1_i386.deb libffi5_3.0.9-1_i386.deb libruby1.9.1_1.9.3.0-1_i386.deb ruby1.9.1_1.9.3.0-1_i386.deb libruby1.9.1-dbg_1.9.3.0-1_i386.deb ruby1.9.1-dev_1.9.3.0-1_i386.deb ri1.9.1_1.9.3.0-1_all.deb ruby1.9.1-examples_1.9.3.0-1_all.deb ruby1.9.1-full_1.9.3.0-1_all.deb ruby1.9.3_1.9.3.0-1_all.deb
	# ignore some errors and run the lines below
	apt-get -f install
	dpkg -i libffi5_3.0.9-1_i386.deb libffi5_3.0.9-1_i386.deb libruby1.9.1_1.9.3.0-1_i386.deb ruby1.9.1_1.9.3.0-1_i386.deb libruby1.9.1-dbg_1.9.3.0-1_i386.deb ruby1.9.1-dev_1.9.3.0-1_i386.deb ri1.9.1_1.9.3.0-1_all.deb ruby1.9.1-examples_1.9.3.0-1_all.deb ruby1.9.1-full_1.9.3.0-1_all.deb ruby1.9.3_1.9.3.0-1_all.deb