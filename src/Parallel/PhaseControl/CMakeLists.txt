# Distributed under the MIT License.
# See LICENSE.txt for details.

spectre_target_headers(
  Parallel
  INCLUDE_DIRECTORY ${CMAKE_SOURCE_DIR}/src
  HEADERS
  ExecutePhaseChange.hpp
  PhaseChange.hpp
  PhaseControlTags.hpp
  VisitAndReturn.hpp
  )
