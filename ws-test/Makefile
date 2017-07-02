CXX ?= clang++
CXXFLAGS += -std=c++11 -Wall -pedantic
LDFLAGS += -lPocoFoundation -lPocoNet -lPocoUtil
BINDIR += bin

.DEFAULT_GOAL := $(BINDIR)/websocketserver

$(BINDIR)/websocketserver: websocketserver.cpp
	$(CXX) $(CXXFLAGS) $(LDFLAGS) -o $@ $+

clean:
	rm -f $(BINDIR)/* 
