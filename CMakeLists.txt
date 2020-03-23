project(udp_client)
project(udp_server)
project(tcp_client)
project(tcp_server)


set(CMAKE_CXX_STANDARD 98)


add_executable(udp_client Assignment-1/udp_client.c)
add_executable(udp_server Assignment-1/udp_server.c)
add_executable(tcp_client Assignment-1/tcp_client.c)
add_executable(tcp_server Assignment-1/tcp_server.c)