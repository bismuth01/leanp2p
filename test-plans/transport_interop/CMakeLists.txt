add_executable(transport_interop_ping
    transport_interop_ping.cpp
)
target_link_libraries(transport_interop_ping
    libp2p
    p2p_protocol_ping
    test_plans_common
)