AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = TcpServer 
TcpServer_SOURCES = main.cpp TcpServer.cpp TcpUser.cpp  DBConnpool.cpp Guide.cpp Point.cpp Util.cpp Location.cpp MsgQueue.cpp
TcpServer_LDADD = -ljson -levent -lmysqlcppconn -lpthread
TcpServer_CXXFLAGS = -I$(top_srcdir)/include
CXXFLAGS = -std=c++11
