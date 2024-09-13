# 易语言-linker

易语言 VC 链接器

- VC 2022

## 常见问题

1. LINK : fatal error LNK1104: 无法打开文件 "libcimt.lib"  
   link.ini 配置 extra_args=/NODEFAULTLIB:"daouuid.lib" /NODEFAULTLIB:"LIBCIMT.LIB" /DEFAULTLIB:"legacy_stdio_definitions.lib" /NODEFAULTLIB:"libc.lib"