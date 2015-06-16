The Web Services Business Process Execution Language (WS-BPEL, BPEL for short) is a programming language to describe the control flow of business processes. BPEL has native support for concurrency, backward and forward recovery. A BPEL process is executed via a workflow engine. Using these engines, a BPEL process can execute for years. IBM, Oracle and Microsoft are some the big players in this field and provide workflow engines which can execute BPEL processes.

The syntax of BPEL is based on XML infoset. Since it is uncommon to write programs using XML, the group around Apache ODE made the proposals BPEL4coders, simBPEL and SimPEL. BPELscript is based on these proposals and provides

  * a compact syntax inspired by scripting languages such as JavaScript and Ruby
  * the full coverage of all features provided by BPEL
  * a translation from WS-BPEL 2.0
  * a translation to WS-BPEL 2.0.

The translation to WS-BPEL 2.0 ensures that BPELscript can be executed on all workflow engines supporting WS-BPEL 2.0. To enable programmers to maintain WS-BPEL 2.0 code, the translation of WS-BPEL 2.0 to BPELscript allows them to modify the code in a syntax more common to programmers.

| &lt;wiki:gadget url="http://www.ohloh.net/p/bpelscript/widgets/project\_basic\_stats.xml" height="220" border="0" /&gt; | &lt;wiki:gadget url="http://www.ohloh.net/p/bpelscript/widgets/project\_factoids.xml" width="340" height="170" border="0" /&gt; |
|:------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------|
| &lt;wiki:gadget url="http://www.ohloh.net/p/bpelscript/widgets/project\_languages.xml" width="340" height="200" border="0" /&gt; | &lt;wiki:gadget url="http://www.ohloh.net/p/bpelscript/widgets/project\_cocomo.xml" height="250" border="0" /&gt;               |