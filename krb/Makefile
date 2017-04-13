TARGET = libkrb.so

SRCS = libkrb.cpp

HEADERS = -I/usr/include/irods/jansson/src

EXTRALIBS = -L/usr/lib/irods/externals -L$(BOOST_DIR)/stage/lib \
	    -lgssapi_krb5 \
            -lboost_chrono -lboost_date_time -lboost_filesystem \
            -lboost_iostreams -lboost_program_options -lboost_regex \
            -lboost_system -lboost_thread

include ../Makefile.base
