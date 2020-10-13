add_message_files(
    FILES
    CosAndSin.msg # <===== HERE =======
)

generate_messages(
    DEPENDENCIES
    std_msgs
)
