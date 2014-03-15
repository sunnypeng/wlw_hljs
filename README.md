wlw_hljs
========
  wlw_hljs is a windows live writer source code plugin based on hightlight.js.
  
  (基于highlight.js的Windows Live Writer源代码高亮插件）
  
  How to use:
  1. put the SourceCodePlugin.dll under your windows live writer plugin folder.
        under 32 bit system the wlw plugin path is: C:\Program Files\Windows Live\Writer\Plugins
        under 64 bit system the wlw plugin path is: C:\Program Files (x86)\Windows Live\Writer\Plugins
        (assume that the C drive is your system drive)
  2. get hightlight.js in http://highlightjs.org/
  3. put the following two lines code in your master pager or header page
      <link rel="stylesheet" title="xcode" href="/hightlight/styles/xcode.css">
      <script type="text/javascript" src="/hightlight/highlight.pack.js"></script>
      <script type="text/javascript">
        // highlight.js init
        hljs.configure({ tabReplace: '    ' });
        hljs.initHighlightingOnLoad();
      </script>
