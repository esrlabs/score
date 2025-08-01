..
   # *******************************************************************************
   # Copyright (c) 2025 Contributors to the Eclipse Foundation
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

Verification Report
===================

.. document:: Persistency Verification Report
   :id: doc__persistency_verification_report
   :status: draft
   :safety: ASIL_B
   :realizes: PROCESS_wp__verification__module_ver_report
   :tags: persistency


This verification report is based on the verification plan.
It covers all the components of the above stated module.

Verification Report contains:

**1. Verification Coverage**

**1.1. on Requirements**
       - Lists of component requirements (incl. AoU satisfied by the component) tested by which test case, passed/failed and completeness verdict
         (this shall be generated by tools and accompanied by progress charts to be usable also for project steering)
       - For external component Assumptions of Use: coverage by platform safety manual or feature/components incl. test case, passed/failed and completeness verdict
       - This is split in a list of QM requirements tested and a separate list of tests for ASIL rated requirements.
       - List of component requirements (ASIL rated) linked to inspection checklist and verdict (derived from PR export)

**1.2. on Architecture**
       - List of component architecture tags tested by which test case, passed/failed and completeness verdict
         (this shall be generated by tools and accompanied by progress charts to be usable also for project steering)
       - This is split in a list of QM components tested and a separate list of tests for ASIL rated components.
       - List of component architecture tags (ASIL rated) linked to inspection checklist and verdict (derived from PR export)

**1.3. on Detailed Design**
       - List of detailed design tags tested by which test case, passed/failed and completeness verdict
         (this shall be generated by tools and accompanied by progress charts to be usable also for project steering)
       - This is split in a list of QM components tested and a separate list of tests for ASIL rated components.
       - List of detailed design tags (ASIL rated) linked to inspection checklist and verdict (derived from PR export)

       - The lists may also contain other verification methods like "Analysis" - process tbd

**2. DFA Report**
       - List of the performed component DFA, pass/fail with open mitigations

**3. Safety Analysis Report**
       - List of the performed component Safety Analysis, pass/fail with open mitigations

**4. Unit Verification Coverage**

**4.1. Structural Coverage**
       - List of the units with C0(line) and C1(branch) coverage absolute and percentage
         (this shall be generated by tools and accompanied by progress charts to be usable also for project steering)
       - List includes a column for the safety rating of each unit.

**4.2. Static Code Analysis**
       - List of the units with compiler warning numbers and coding rule violation numbers
         (this shall be generated by tools and accompanied by progress charts to be usable also for project steering)
       - List includes a column for the safety rating of each unit.

**4.3. Manual Code Inspection**
       - List of components (ASIL rated) linked to inspection checklist and verdict (derived from PR export)

**5. Software component qualification verification report**
       - Contains the needed verification results if for some components a qualification of pre-developed SW is performed.

**Note1:** The verification report is valid for the module version tagged together with the report

**Note2:** All the above lists are generated automatically
