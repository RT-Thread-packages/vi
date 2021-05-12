Import('rtconfig')
from building import *

src     = Glob('*.c')
group = DefineGroup('vi', src, depend = ['PKG_USING_VI', 'RT_USING_DFS'])
Return('group')
