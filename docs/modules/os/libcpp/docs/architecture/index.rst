..
   # *******************************************************************************
   # Copyright (c) 2026 Contributors to the Eclipse Foundation
   #
   # See the NOTICE file(s) distributed with this work for additional
   # information regarding copyright ownership.
   #
   # This program and the accompanying materials are made available under the
   # terms of the Apache License Version 2.0 which is available at
   # https://www.apache.org/licenses/LICENSE-2.0
   #
   # SPDX-License-Identifier: Apache-2.0
   # *******************************************************************************

libcpp Component Architecture
*****************************

.. comp:: libcpp
   :id: comp__os_libcpp
   :status: valid
   :safety: ASIL_B
   :implements: logic_arc_int__os__libcpp
   :security: YES

.. comp_arc_sta:: C++ Std Library
   :id: comp_arc_sta__os__libcpp
   :security: YES
   :safety: ASIL_B
   :status: valid
   :satisfies:
   :belongs_to: comp__os_libcpp
   :fulfils: comp_req__component_name__some_title

   .. needarch::
      :scale: 50
      :align: center

      {{ draw_component(need(), needs) }}

.. logic_arc_int:: Library headers (C++17)
   :id: logic_arc_int__os__libcpp
   :security: YES
   :safety: ASIL_B
   :status: valid

   .. needarch::
      :scale: 50
      :align: center

      {{ draw_interface(need(), needs) }}
