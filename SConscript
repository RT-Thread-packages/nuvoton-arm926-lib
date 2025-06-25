import os
from building import *

objs = []
cwd  = GetCurrentDir()

if GetDepend(['SOC_SERIES_N9H30']):
    objs = objs + SConscript('N9H30/SConscript')

if GetDepend(['SOC_SERIES_NUC980']):
    objs = objs + SConscript('NUC980/SConscript')

Return('objs')