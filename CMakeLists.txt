# Copyright (C) 2011 LuaDist.
# Created by Peter Drahos
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT(oil C)
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
INCLUDE(dist.cmake)

INSTALL(DIRECTORY lua/oil DESTINATION ${INSTALL_LMOD})
INSTALL(DIRECTORY doc/ DESTINATION ${INSTALL_DOC})
INSTALL(DIRECTORY demo/ DESTINATION ${INSTALL_TEST})
