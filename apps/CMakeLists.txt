# Copyright 2011 Free Software Foundation, Inc.
#
# This file was generated by gr_modtool, a tool from the GNU Radio framework
# This file is a part of gr-pager
#
# SPDX-License-Identifier: GPL-3.0-or-later
#

include(GrPython)

GR_PYTHON_INSTALL(
    PROGRAMS
    flex_band
    usrp_flex
    usrp_flex_all
    usrp_flex_band
    DESTINATION ${GR_RUNTIME_DIR}
    COMPONENT "pager_python"
)
