add_executable(custom_message_node_sub exercise_4_3_sub.cpp)
target_link_libraries(custom_message_node_sub ${catkin_LIBRARIES})
# manually added
# add_dependencies(custom_message_node_sub ${catkin_EXPORTED_TARGETS})

add_executable(custom_message_node_pub exercise_4_3_pub.cpp)
target_link_libraries(custom_message_node_pub ${catkin_LIBRARIES})
# manually added
# add_dependencies(custom_message_node_pub ${catkin_EXPORTED_TARGETS})
