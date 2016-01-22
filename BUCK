include_defs('//ReactAndroid/DEFS')

android_library(
  name = 'art',
  srcs = glob(['*.java']),
  deps = [
    react_native_target('java/com/facebook/react/bridge:bridge'),
    react_native_target('java/com/facebook/react/common:common'),
    react_native_target('java/com/facebook/csslayout:csslayout'),
    react_native_target('java/com/facebook/react/uimanager:uimanager'),
    react_native_target('java/com/facebook/react/uimanager/annotations:annotations'),
    react_native_dep('libraries/fbcore/src/main/java/com/facebook/common/logging:logging'),
    react_native_dep('third-party/java/jsr-305:jsr-305'),
  ],
  visibility = [
    'PUBLIC',
  ],
)

project_config(
  src_target = ':art',
)
