add_executable(EquityOption EquityOption.cpp)
target_link_libraries(EquityOption ${QL_LINK_LIBRARY} ${Boost_LIBRARIES})