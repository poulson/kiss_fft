#  Copyright (c) 2014, Jack Poulson
#  All rights reserved.
#
#  This file is part of KISS-FFT and is under the BSD 2-Clause License, 
#  which can be found in the LICENSE file in the root directory, or at 
#  http://opensource.org/licenses/BSD-2-Clause
#
project(kiss_fft)
cmake_minimum_required(VERSION 2.8.8)
add_library(kiss_fft kiss_fft.c)
install(FILES kiss_fft.h DESTINATION include)
install(TARGETS kiss_fft DESTINATION lib)
