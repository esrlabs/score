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

.. document:: Tool Evaluation List
   :id: doc__tool_evaluation_list
   :status: draft
   :safety: ASIL_B
   :security: YES
   :realizes: wp__tool_verification_report
   :tags: tool_management


.. contents:: Table of Contents
   :depth: 3
   :local:


S-CORE - Complete Tool List for Tool Evaluation
===============================================

Overview
--------

This document provides a comprehensive initial inventory of all tools used across the Eclipse
S-CORE project.

The list is categorized by tool type, e.g. documentation tools, static analysis tools, testing
frameworks, build tools, etc.

The list is intended to be used for the evaluation of tools for safety and security impact, as part
of the tool management process defined in the S-CORE Tool Management Plan.

In future iterations, the list will be completed and updated, and delivered with every platform
release, as part of the Tool Verification Report.


1 Documentation Tools
---------------------

.. list-table:: Documentation Tools
   :header-rows: 1
   :widths: 5 15 15 10 10 10 40 40

   * - ID
     - Tool Name
     - Description
     - Version
     - Relevant [YES|NO]
     - Tool ownership
     - Link to Verification Report (if relevant)
     - Confirmation of Use [YES|NO] (if relevant)
   * - 1-1
     - Doc-as-Code
     - Documentation generation tool
     - 3.0.0 (see [1]_)
     - YES
     - :need:`rl__infrastructure_tooling_community`
     - :need:`doc_tool__doc_as_code`
     - YES
   * - 1-2
     - Sphinx
     - Python documentation generator (underlying Doc-as-Code)
     - Latest (see [1]_)
     - YES
     - :need:`rl__infrastructure_tooling_community`
     - :need:`doc_tool__doc_as_code`
     - YES



2 Static Analysis & Code Quality
--------------------------------


2a C++
++++++


2b Rust
+++++++

.. list-table:: Rust Static Analysis & Code Quality
   :header-rows: 1
   :widths: 5 15 15 10 10 10 40 40

   * - ID
     - Tool Name
     - Description
     - Version
     - Relevant [YES|NO]
     - Tool ownership
     - Link to Verification Report (if relevant)
     - Confirmation of Use [YES|NO] (if relevant)
   * - 2b-1
     - clippy
     - Rust linter for static code analysis
     - 1.90.0 (see [1]_)
     - YES
     - :need:`rl__infrastructure_tooling_community`
     - :need:`doc_tool__clippy`
     - YES
   * - 2b-2
     - Sphinx
     - Rust code formatter
     - 1.8.0 (see [1]_)
     - YES
     - :need:`rl__infrastructure_tooling_community`
     - :need:`doc_tool__rustfmt`
     - YES

2c Python
+++++++++



2d Other
++++++++




3 Testing Frameworks
--------------------

.. list-table:: Testing Frameworks
   :header-rows: 1
   :widths: 5 15 15 10 10 10 40 40

   * - ID
     - Tool Name
     - Description
     - Version
     - Relevant [YES|NO]
     - Tool ownership
     - Link to Verification Report (if relevant)
     - Confirmation of Use [YES|NO] (if relevant)
   * - 3-1
     - gtest (GoogleTest)
     - C++ testing framework
     - 1.15.0 (see [1]_)
     - YES
     - :need:`rl__infrastructure_tooling_community`
     - :need:`doc_tool__gtest`
     - YES
   * - 3-2
     - ITF
     - Integration Testing Framework, pytest-based
     - 0.1.0 (see [1]_)
     - YES
     - :need:`rl__infrastructure_tooling_community`
     - :need:`doc_tool__itf`
     - YES


4 Build & Development Tools
---------------------------

.. list-table:: Build & Development Tools
   :header-rows: 1
   :widths: 5 15 15 10 10 10 40 40

   * - ID
     - Tool Name
     - Description
     - Version
     - Relevant [YES|NO]
     - Tool ownership
     - Link to Verification Report (if relevant)
     - Confirmation of Use [YES|NO] (if relevant)
   * - 4-1
     - Bazel
     - Main build system
     - 8.3.0 (see [1]_)
     - YES
     - :need:`rl__infrastructure_tooling_community`
     - :need:`doc_tool__bazel`
     - YES



.. [1] The tool version mentioned in this document is preliminary.
       Exact version must be derived before every platform release.
