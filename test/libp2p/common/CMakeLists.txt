##
# Copyright Soramitsu Co., Ltd. All Rights Reserved.
# SPDX-License-Identifier: Apache-2.0
##

addtest(hexutil_test
  hexutil_test.cpp
  )
target_link_libraries(hexutil_test
  p2p_hexutil
  p2p_literals
  )
