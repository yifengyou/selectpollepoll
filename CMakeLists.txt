CMAKE_MINIMUM_REQUIRED(VERSION 3.19)
PROJECT(selectpollepoll)

SET(CMAKE_CXX_STANDARD 14)

ADD_EXECUTABLE(epollclient src/epoll/client.cpp)
ADD_EXECUTABLE(epollserver src/epoll/tcpepoll.cpp)
ADD_EXECUTABLE(pollclient src/poll/client.cpp)
ADD_EXECUTABLE(pollserver src/poll/tcppoll.cpp)
ADD_EXECUTABLE(selectclient src/select/client.cpp)
ADD_EXECUTABLE(selectserver src/select/tcpselect.cpp)
