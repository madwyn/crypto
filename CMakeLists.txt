project(mad-crypto)

set(AES_GLADMAN_ROOT ${CMAKE_CURRENT_LIST_DIR}/aes)
add_subdirectory(aes-gladman-cmake)
set(CRC8_ROOT ${CMAKE_CURRENT_LIST_DIR}/CRC8)
add_subdirectory(crc8-cmake)
add_subdirectory(crc16)
add_subdirectory(keccak)
add_subdirectory(mad-hmac)
