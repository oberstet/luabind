################################################################################
##
## Copyright (c) 2011, Tavendo GmbH. All rights reserved.
##
################################################################################

Import ('env')

localenv = env.Clone ()
localenv.Append (CPPDEFINES = ['NDEBUG'])

SOURCES = Glob ('src/*.cpp')

luabind = localenv.StaticLibrary ('luabind', SOURCES)

Return ('luabind')
