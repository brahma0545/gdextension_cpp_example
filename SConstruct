import os
import sys
env = SConscript("godot-cpp/SConstruct")
env.Append(CPPPATH=["src/"])
sources = Glob("src/*.cpp")
print(sources)
library = env.SharedLibrary("3DOTS/bin/libgdexample.windows.template_debug.x86_64.dll", source=sources,)
print("librar",library)
Default(library)
