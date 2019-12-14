#文件已经都核对过数量,结构关系了
set(CRNLIB_DIR ${CMAKE_CURRENT_SOURCE_DIR}/src)
set(CRNLIB_INC ${CMAKE_CURRENT_SOURCE_DIR}/inc)

set(crn_src_api 
${CRNLIB_DIR}/crnlib.cpp
)

set(crn_src_comp 
${CRNLIB_DIR}/crn_clusterizer.h
${CRNLIB_DIR}/crn_dxt.h
${CRNLIB_DIR}/crn_dxt1.h
${CRNLIB_DIR}/crn_dxt5a.h
${CRNLIB_DIR}/crn_dxt_endpoint_refiner.h
${CRNLIB_DIR}/crn_dxt_fast.h
${CRNLIB_DIR}/crn_dxt_hc_common.h
${CRNLIB_DIR}/crn_etc.h
${CRNLIB_DIR}/crn_huffman_codes.h
${CRNLIB_DIR}/crn_lzma_codec.h
${CRNLIB_DIR}/crn_miniz.h
${CRNLIB_DIR}/crn_prefix_coding.h
${CRNLIB_DIR}/crn_qdxt1.h
${CRNLIB_DIR}/crn_qdxt5.h
${CRNLIB_DIR}/crn_rg_etc1.h
${CRNLIB_DIR}/crn_ryg_dxt.hpp
${CRNLIB_DIR}/crn_ryg_types.hpp
${CRNLIB_DIR}/crn_symbol_codec.h
${CRNLIB_DIR}/crn_threaded_clusterizer.h
${CRNLIB_DIR}/crn_tree_clusterizer.h
${CRNLIB_DIR}/crn_dxt.cpp
${CRNLIB_DIR}/crn_dxt1.cpp
${CRNLIB_DIR}/crn_dxt5a.cpp
${CRNLIB_DIR}/crn_dxt_endpoint_refiner.cpp
${CRNLIB_DIR}/crn_dxt_fast.cpp
${CRNLIB_DIR}/crn_dxt_hc_common.cpp
${CRNLIB_DIR}/crn_etc.cpp
${CRNLIB_DIR}/crn_huffman_codes.cpp
${CRNLIB_DIR}/crn_lzma_codec.cpp
${CRNLIB_DIR}/crn_miniz.cpp
${CRNLIB_DIR}/crn_prefix_coding.cpp
${CRNLIB_DIR}/crn_qdxt1.cpp
${CRNLIB_DIR}/crn_qdxt5.cpp
${CRNLIB_DIR}/crn_rg_etc1.cpp
${CRNLIB_DIR}/crn_ryg_dxt.cpp
${CRNLIB_DIR}/crn_symbol_codec.cpp
)
 
set(crn_src_math 
${CRNLIB_DIR}/crn_intersect.h
${CRNLIB_DIR}/crn_math.h
${CRNLIB_DIR}/crn_matrix.h
${CRNLIB_DIR}/crn_rand.h
${CRNLIB_DIR}/crn_ray.h
${CRNLIB_DIR}/crn_rect.h
${CRNLIB_DIR}/crn_vec.h
${CRNLIB_DIR}/crn_vec_interval.h
${CRNLIB_DIR}/crn_math.cpp
${CRNLIB_DIR}/crn_rand.cpp
)

set(crn_src_containers 
${CRNLIB_DIR}/crn_hash_map.h
${CRNLIB_DIR}/crn_sparse_array.h
${CRNLIB_DIR}/crn_sparse_bit_array.h
${CRNLIB_DIR}/crn_value.h
${CRNLIB_DIR}/crn_vector.h
${CRNLIB_DIR}/crn_vector2d.h
${CRNLIB_DIR}/crn_hash_map.cpp
${CRNLIB_DIR}/crn_sparse_bit_array.cpp
${CRNLIB_DIR}/crn_value.cpp
${CRNLIB_DIR}/crn_vector.cpp
)
 
set(crn_src_image 
${CRNLIB_DIR}/crn_color.h
${CRNLIB_DIR}/crn_image.h
${CRNLIB_DIR}/crn_image_utils.h
${CRNLIB_DIR}/crn_jpgd.h
${CRNLIB_DIR}/crn_jpge.h
${CRNLIB_DIR}/crn_pixel_format.h
${CRNLIB_DIR}/crn_resample_filters.h
${CRNLIB_DIR}/crn_resampler.h
${CRNLIB_DIR}/crn_threaded_resampler.h
${CRNLIB_DIR}/crn_image_utils.cpp
${CRNLIB_DIR}/crn_jpgd.cpp
${CRNLIB_DIR}/crn_jpge.cpp
${CRNLIB_DIR}/crn_pixel_format.cpp
${CRNLIB_DIR}/crn_resample_filters.cpp
${CRNLIB_DIR}/crn_resampler.cpp
${CRNLIB_DIR}/crn_stb_image.cpp
${CRNLIB_DIR}/crn_threaded_resampler.cpp
)

set(crn_src_string 
${CRNLIB_DIR}/crn_dynamic_string.h
${CRNLIB_DIR}/crn_strutils.h
${CRNLIB_DIR}/crn_dynamic_string.cpp
${CRNLIB_DIR}/crn_strutils.cpp
)
 
set(crn_src_utils 
${CRNLIB_DIR}/crn_arealist.h
${CRNLIB_DIR}/crn_checksum.h
${CRNLIB_DIR}/crn_command_line_params.h
${CRNLIB_DIR}/crn_hash.h
${CRNLIB_DIR}/crn_helpers.h
${CRNLIB_DIR}/crn_packed_uint.h
${CRNLIB_DIR}/crn_radix_sort.h
${CRNLIB_DIR}/crn_timer.h
${CRNLIB_DIR}/crn_traits.h
${CRNLIB_DIR}/crn_utils.h
${CRNLIB_DIR}/crn_arealist.cpp
${CRNLIB_DIR}/crn_checksum.cpp
${CRNLIB_DIR}/crn_command_line_params.cpp
${CRNLIB_DIR}/crn_hash.cpp
${CRNLIB_DIR}/crn_timer.cpp
${CRNLIB_DIR}/crn_utils.cpp
)

set(crn_src_stream 
${CRNLIB_DIR}/crn_buffer_stream.h
${CRNLIB_DIR}/crn_cfile_stream.h
${CRNLIB_DIR}/crn_data_stream.h
${CRNLIB_DIR}/crn_data_stream_serializer.h
${CRNLIB_DIR}/crn_dynamic_stream.h
${CRNLIB_DIR}/crn_data_stream.cpp
)
 
set(crn_src_console 
${CRNLIB_DIR}/crn_colorized_console.h
${CRNLIB_DIR}/crn_console.h
${CRNLIB_DIR}/crn_colorized_console.cpp
${CRNLIB_DIR}/crn_console.cpp
)

set(crn_src_threading 
${CRNLIB_DIR}/crn_threading.h
${CRNLIB_DIR}/crn_threading_null.h
${CRNLIB_DIR}/crn_threading_win32.h
${CRNLIB_DIR}/crn_threading_win32.cpp
)

set(crn_src_lzmalib 
${CRNLIB_DIR}/lzma_7zBuf.h
${CRNLIB_DIR}/lzma_7zCrc.h
${CRNLIB_DIR}/lzma_7zFile.h
${CRNLIB_DIR}/lzma_7zVersion.h
${CRNLIB_DIR}/lzma_Alloc.h
${CRNLIB_DIR}/lzma_Bcj2.h
${CRNLIB_DIR}/lzma_Bra.h
${CRNLIB_DIR}/lzma_CpuArch.h
${CRNLIB_DIR}/lzma_LzFind.h
${CRNLIB_DIR}/lzma_LzFindMt.h
${CRNLIB_DIR}/lzma_LzHash.h
${CRNLIB_DIR}/lzma_LzmaDec.h
${CRNLIB_DIR}/lzma_LzmaEnc.h
${CRNLIB_DIR}/lzma_LzmaLib.h
${CRNLIB_DIR}/lzma_MyVersion.h
${CRNLIB_DIR}/lzma_Threads.h
${CRNLIB_DIR}/lzma_Types.h
${CRNLIB_DIR}/lzma_7zBuf.cpp
${CRNLIB_DIR}/lzma_7zBuf2.cpp
${CRNLIB_DIR}/lzma_7zCrc.cpp
${CRNLIB_DIR}/lzma_7zFile.cpp
${CRNLIB_DIR}/lzma_7zStream.cpp
${CRNLIB_DIR}/lzma_Alloc.cpp
${CRNLIB_DIR}/lzma_Bcj2.cpp
${CRNLIB_DIR}/lzma_Bra.cpp
${CRNLIB_DIR}/lzma_Bra86.cpp
${CRNLIB_DIR}/lzma_BraIA64.cpp
${CRNLIB_DIR}/lzma_LzFind.cpp
${CRNLIB_DIR}/lzma_LzFindMt.cpp
${CRNLIB_DIR}/lzma_LzmaDec.cpp
${CRNLIB_DIR}/lzma_LzmaEnc.cpp
${CRNLIB_DIR}/lzma_LzmaLib.cpp
${CRNLIB_DIR}/lzma_Threads.cpp
)

set(crn_src_crn 
${CRNLIB_DIR}/crn_comp.h
${CRNLIB_DIR}/crn_dds_comp.h
${CRNLIB_DIR}/crn_dxt_hc.h
${CRNLIB_DIR}/crn_texture_comp.h
${CRNLIB_DIR}/crn_comp.cpp
${CRNLIB_DIR}/crn_dds_comp.cpp
${CRNLIB_DIR}/crn_decomp.cpp
${CRNLIB_DIR}/crn_dxt_hc.cpp
${CRNLIB_DIR}/crn_texture_comp.cpp
)
 
set(crn_src_texture_conversion 
${CRNLIB_DIR}/crn_texture_conversion.h
${CRNLIB_DIR}/crn_texture_file_types.h
${CRNLIB_DIR}/crn_texture_conversion.cpp
${CRNLIB_DIR}/crn_texture_file_types.cpp
)

set(crn_src_inc 
${CRNLIB_INC}/crn_decomp.h
${CRNLIB_INC}/crn_defs.h
${CRNLIB_INC}/crnlib.h
${CRNLIB_INC}/dds_defs.h
)

set(crn_src_file 
${CRNLIB_DIR}/crn_file_utils.h
${CRNLIB_DIR}/crn_find_files.h
${CRNLIB_DIR}/crn_file_utils.cpp
${CRNLIB_DIR}/crn_find_files.cpp
)

set(crn_src_texture 
${CRNLIB_DIR}/crn_dxt_image.h
${CRNLIB_DIR}/crn_ktx_texture.h
${CRNLIB_DIR}/crn_mipmapped_texture.h
${CRNLIB_DIR}/crn_dxt_image.cpp
${CRNLIB_DIR}/crn_ktx_texture.cpp
${CRNLIB_DIR}/crn_mipmapped_texture.cpp
)

set(crn_src 
${CRNLIB_DIR}/crn_assert.h
${CRNLIB_DIR}/crn_atomics.h
${CRNLIB_DIR}/crn_core.h
${CRNLIB_DIR}/crn_mem.h
${CRNLIB_DIR}/crn_platform.h
${CRNLIB_DIR}/crn_types.h
${CRNLIB_DIR}/crn_winhdr.h
${CRNLIB_DIR}/crn_assert.cpp
${CRNLIB_DIR}/crn_core.cpp
${CRNLIB_DIR}/crn_mem.cpp
${CRNLIB_DIR}/crn_platform.cpp
)

#231-52 = 179
#11

source_group("api" FILES ${crn_src_api})
source_group("comp" FILES ${crn_src_comp})
source_group("math" FILES ${crn_src_math})
source_group("containers" FILES ${crn_src_containers})
source_group("image" FILES ${crn_src_image})
source_group("string" FILES ${crn_src_string})
source_group("utils" FILES ${crn_src_utils})
source_group("stream" FILES ${crn_src_stream})
source_group("console" FILES ${crn_src_console})
source_group("threading" FILES ${crn_src_threading})
source_group("lzmalib" FILES ${crn_src_lzmalib})
source_group("crn" FILES ${crn_src_crn})
source_group("conversion" FILES ${crn_src_texture_conversion})
source_group("inc" FILES ${crn_src_inc})
source_group("file" FILES ${crn_src_file})
source_group("texture" FILES ${crn_src_texture})


source_group("" FILES ${crn_src})

#crn_src_api
#crn_src_comp
#crn_src_math
#crn_src_containers
#crn_src_image
#crn_src_string
#crn_src_utils
#crn_src_stream
#crn_src_console
#crn_src_threading
#crn_src_lzmalib
#crn_src_crn
#crn_src_texture_conversion
#crn_src_inc
#crn_src_file
#crn_src_texture
#crn_src

set(ALLFILES 
${crn_src_api} 
${crn_src_comp}
${crn_src_math}
${crn_src_containers}
${crn_src_image}
${crn_src_string}
${crn_src_utils}
${crn_src_stream}
${crn_src_console}
${crn_src_threading}
${crn_src_lzmalib}
${crn_src_crn}
${crn_src_texture_conversion}
${crn_src_inc}
${crn_src_file}
${crn_src_texture}
${crn_src}
)

 #macro(_pch SRCS PCHCPP)
  #if(MSVC AND CMAKE_GENERATOR MATCHES "^Visual Studio")
  #  set(PCH_NAME "$(IntDir)\\crn_core.pch")
   # # make source files use/depend on PCH_NAME
    #set_source_files_properties(${${SRCS}} PROPERTIES COMPILE_FLAGS "/Yupch.h /FIpch.h /Fp${PCH_NAME} /Zm300" OBJECT_DEPENDS "${PCH_NAME}")
    ## make PCHCPP file compile and generate PCH_NAME
    #set_source_files_properties(${PCHCPP} PROPERTIES COMPILE_FLAGS "/Ycpch.h /Fp${PCH_NAME} /Zm300" OBJECT_OUTPUTS "${PCH_NAME}")
    #list(APPEND ${SRCS} "${PCHCPP}")
  #endif()
  #endmacro(_pch)

#_pch(ALLFILES ${CRNLIB_DIR}/crn_core.cpp)

add_library(crnlib ${ALLFILES})


 
 
 