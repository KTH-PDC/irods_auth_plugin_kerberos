TARGET = libkrb.so

SRCS = libkrb.cpp

HEADERS = -I/usr/include/irods/jansson/src

EXTRALIBS = /usr/lib/libirods_client.a \
            -lgssapi_krb5 \
            -L/usr/lib/irods/externals \
            -lboost_chrono -lboost_date_time -lboost_filesystem \
            -lboost_iostreams -lboost_program_options -lboost_regex \
            -lboost_system -lboost_thread

include ../Makefile.base
