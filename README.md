# 易语言-linker
易语言VC链接器


# VC 2022
如果配置使用VS2022的链接器，link.ini中除了正常配置 linker 之外，还必须在 extra_args 节点下配置下面的内容
extra_args=/DYNAMICBASE "legacy_stdio_definitions.lib"