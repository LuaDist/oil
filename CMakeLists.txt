# Copyright (C) 2012 LuaDist.
# Created by Peter Drahos
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.
project ( oil C )
cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )
include ( lua )

install ( DIRECTORY lua/oil DESTINATION ${INSTALL_LMOD} COMPONENT Runtime)
install_doc ( doc/ )
install_example ( demo/  )
install_data ( LICENSE )
