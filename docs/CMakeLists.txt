# Copyright 2016 The Cartographer Authors
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

cmake_minimum_required(VERSION 3.5)

project(cartographer_ros_docs)

find_package(Sphinx)
if(SPHINX_FOUND)
  set(OUTPUT_DIR "${PROJECT_BINARY_DIR}/docs/html")
  add_custom_target(build_doc_ros ALL
      ${SPHINX_EXECUTABLE} -b html
      ${CMAKE_CURRENT_SOURCE_DIR}/source
      ${CMAKE_CURRENT_BINARY_DIR}/html
      COMMENT "Building documentation."
  )
endif()
