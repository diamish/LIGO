add_executable(test_hdf5reader src/test_hdf5reader.cpp src/HDF5Reader.cpp)
target_link_libraries(test_hdf5reader PRIVATE ${HDF5_LIBRARIES})

