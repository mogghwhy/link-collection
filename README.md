# link-collection
* [WinDbg](#WinDbg)
* [Garbage Collection](#GC)
* [Debugging](#Debugging)
* [Clr](#CLR)

## WinDbg
| Name                                                                       | Description                                                                        |
|----------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| [What is WinDbg?](https://learn.microsoft.com/en-us/windows-hardware/drivers/debuggercmds/windbg-overview) [archive.today](https://archive.ph/aGsU8)| learn.microsoft.com, Article 08/26/2024 |
| [Get started with WinDbg (user mode)](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/getting-started-with-windbg) [archive.today](https://archive.is/blrZ2)| learn.microsoft.com, Article 12/28/2023 |
| [WinDBG quick start tutorial](https://codemachine.com/articles/windbg_quickstart.html) [archive.org](http://web.archive.org/web/20240324162937/https://codemachine.com/articles/windbg_quickstart.html) [archive.today](https://archive.ph/RANiR)| |
| [Common WinDbg Commands (Thematically Grouped)](http://windbg.info/doc/1-common-cmds.html) [archive.today](https://archive.ph/AMJxT)| |
| [CrashMe Application](http://windbg.info/apps/46-crashme.html) [arhive.org](http://web.archive.org/web/20240419221017/http://windbg.info/apps/46-crashme.html) | from http://windbg.info |
| [WinDbg. From A to Z!](http://www.windbg.info/doc/2-windbg-a-z.html) [archive.org](http://web.archive.org/web/20240423081410/http://www.windbg.info/doc/2-windbg-a-z.html) | from http://windbg.info, [presentation pdf](http://web.archive.org/web/20240411085442/http://windbg.info/download/doc/pdf/WinDbg_A_to_Z_color.pdf) |
| [Learn WinDbg](http://www.windbg.xyz) [archive.today](https://archive.ph/JkpmO) ||
| [Traversing the gc heap (and introducing PSSCOR.DLL)](https://learn.microsoft.com/en-us/archive/blogs/mvstanton/traversing-the-gc-heap-and-introducing-psscor-dll) [archive.today](https://archive.ph/iys9H) | mvstanton's WebLog - Article 04/05/2004 |
| [Some new SOS functions](https://learn.microsoft.com/en-us/archive/blogs/mvstanton/some-new-sos-functions) [archive.today](https://archive.ph/W2fQV) | mvstanton's WebLog - Article 10/11/2005 |
| [SOS.dll (SOS debugging extension)](https://learn.microsoft.com/en-us/dotnet/framework/tools/sos-dll-sos-debugging-extension) | |
| [Debugging Tips: Use windbg as a calculator, a chat client and more](https://www.tessferrandez.com/blog/2006/01/18/debugging-tips-use-windbg-as-a-calculator.html) [archive.today](https://archive.ph/mwpmW) ||
| [Getting Started with Windbg](https://www.tessferrandez.com/blog/2007/11/19/getting-started-with-windbg.html) [archive.today](https://archive.ph/RmqXw) | Tess Ferrandez's blog post, November 19, 2007, EDIT (30 Sept 2020) |
| [Getting started with windbg - part II ](https://www.tessferrandez.com/blog/2007/11/26/getting-started-with-windbg-part-ii.html) [archive.today](https://archive.ph/AvBvH) | Tess Ferrandez's blog post, November 26, 2007, Update 2021 |
| [Using WinDbg - Advanced commands](https://www.tessferrandez.com/blog/2008/01/23/windbg-advanced-commands.html) [archive.today](https://archive.ph/pcd6W)| Update 2021: This is a re-post of a post from Johan Straarup |
| [Correlating the output of !eeheap -gc and !address](https://devblogs.microsoft.com/dotnet/correlating-the-output-of-eeheap-gc-and-address/) [archive.today](https://archive.ph/8QIjA) | November 8th, 2006 |
| [WinDbg the easy way](https://www.debuginfo.com/articles/easywindbg.html) [archive.org](https://web.archive.org/web/20230923131137/https://www.debuginfo.com/articles/easywindbg.html) [archive.today](https://archive.ph/souKi) |  |
| [WinDbg the easy way (Part 2)](https://www.debuginfo.com/articles/easywindbg.html) [archive.org](https://web.archive.org/web/20240711224154/https://debuginfo.com/articles/easywindbg2.html) [archive.today](https://archive.ph/yHOrk) |  |


## GC
| Name                                                                       | Description                                                                        |
|----------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| [.NET Memory Performance Analysis](https://github.com/Maoni0/mem-doc/blob/master/doc/.NETMemoryPerformanceAnalysis.md) [archive.today](https://archive.ph/PrWlh) [archive.org](https://web.archive.org/web/20240913230707/https://github.com/Maoni0/mem-doc/blob/master/doc/.NETMemoryPerformanceAnalysis.md) - 13 Sep 2024 ||
| [Internals of the POH](https://devblogs.microsoft.com/dotnet/internals-of-the-poh/) [archive.org](https://web.archive.org/web/20240607094136/https://devblogs.microsoft.com/dotnet/internals-of-the-poh/) [archive.today](https://archive.ph/9nJXv) | February 27th, 2021 |
| [Investigating Memory Issues](https://learn.microsoft.com/en-us/archive/msdn-magazine/2006/november/clr-inside-out-investigating-memory-issues) [https://web.archive.org/web/20070509225024/http://msdn.microsoft.com/msdnmag/issues/06/11/CLRInsideOut/default.aspx?loc=en](archive.org) [https://archive.ph/MqcIP](archive.today)  | Claudio Caldato and Maoni Stephens |
| [Mid-life crisis](https://learn.microsoft.com/en-us/archive/blogs/ricom/mid-life-crisis) [archive.org](https://web.archive.org/web/20070514065708/http://blogs.msdn.com/ricom/archive/2003/12/04/41281.aspx) [archive.today](https://archive.ph/6VydP) | Rico Mariani's Performance Tidbits, December 2003 |
| [Using GC Efficiently – Part 1](https://devblogs.microsoft.com/dotnet/using-gc-efficiently-part-1/) [archive.org](https://web.archive.org/web/20240607094058/https://devblogs.microsoft.com/dotnet/using-gc-efficiently-part-1/) [archive.today](https://archive.ph/42F7l) | June 15th, 2004 |
| [Garbage Collection: Automatic Memory Management in the Microsoft .NET Framework](https://learn.microsoft.com/en-us/archive/msdn-magazine/2000/november/garbage-collection-automatic-memory-management-in-the-microsoft-net-framework) [archive.org](https://web.archive.org/web/20070509224330/http://msdn.microsoft.com/msdnmag/issues/1100/GCI/default.aspx) [archive.today](https://archive.ph/g6fm4) | Jeffrey Richter, MSDN Magazine , November 2000 |
| [Garbage Collection—Part 2: Automatic Memory Management in the Microsoft .NET Framework](https://learn.microsoft.com/en-us/archive/msdn-magazine/2000/december/garbage-collection-part-2-automatic-memory-management-in-the-microsoft-net-framework) [archive.org](https://web.archive.org/web/20070512214802/http://msdn.microsoft.com/msdnmag/issues/1200/GCI2/) [archive.today](https://archive.ph/AaSDU) | Jeffrey Richter, MSDN Magazine , December 2000 |
| [Using GC Efficiently – Part 2](https://devblogs.microsoft.com/dotnet/using-gc-efficiently-part-2/) [archive.org](https://web.archive.org/web/20240609085207/https://devblogs.microsoft.com/dotnet/using-gc-efficiently-part-2/) [archive.today](https://archive.ph/NAowO)| September 25th, 2004 |
| [Using GC Efficiently – Part 3](https://devblogs.microsoft.com/dotnet/using-gc-efficiently-part-3/) [archive.org](https://web.archive.org/web/20240607094156/https://devblogs.microsoft.com/dotnet/using-gc-efficiently-part-3/) [archive.today](https://archive.ph/65i45)| December 19th, 2004 |
| [Using GC Efficiently – Part 4](https://devblogs.microsoft.com/dotnet/using-gc-efficiently-part-4/) [archive.org](https://web.archive.org/web/20240607094526/https://devblogs.microsoft.com/dotnet/using-gc-efficiently-part-4/) [archive.today](https://archive.ph/wdTGg)| May 6th, 2005 |
| [Tools that help diagnose managed memory related issues](https://devblogs.microsoft.com/dotnet/tools-that-help-diagnose-managed-memory-related-issues/) [archive.today](https://archive.ph/fB9jA) | devblogs.microsoft.com article, November 8th, 2004 |
| [.NET GC Internals](https://www.youtube.com/playlist?list=PLpUkQYy-K8Y-wYcDgDXKhfs6OT8fFQtVm) | youtube playlist, .NET GC Internals series explaining a real in-depth knowledge how .NET GC works. |
| [Put a DPAD on that GC!](https://devblogs.microsoft.com/dotnet/put-a-dpad-on-that-gc/) [archive.today](https://archive.ph/AdujA)| devblogs.microsoft.com article, May 10th, 2021 |
| [Garbage collection and performance](https://learn.microsoft.com/en-us/dotnet/standard/garbage-collection/performance) [archive.today](https://archive.ph/CxLSz) | learn.microsoft.com, Article 07/12/2022 |
| [GC Performance Counters](https://devblogs.microsoft.com/dotnet/gc-performance-counters/) [archive.org](https://web.archive.org/web/20051123014042/http://blogs.msdn.com/maoni/archive/2004/06/03/148029.aspx) [archive.today](https://archive.ph/VwLhZ)| posted on Thursday, June 03, 2004 3:46 PM by maoni |


## Debugging
| Name                                                                       | Description                                                                        |
|----------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| [Get started with Windows debugging](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/getting-started-with-windows-debugging) [archive.today](https://archive.is/7mOG5)| learn.microsoft.com, Article 12/20/2023 |
| [Debugging Techniques](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/debugging-techniques) [archive.today](https://archive.ph/PiJpZ)| learn.microsoft.com, Article 12/15/2021 |
| [Standard Debugging Techniques](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/standard-debugging-techniques) [archive.today](https://archive.ph/8vQus) | learn.microsoft.com, Article 12/15/2021 |
| [Specialized Debugging Techniques](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/specialized-debugging-techniques) [archive.today](https://archive.ph/kqkt4) | learn.microsoft.com, Article 05/20/2022 |
| [Deep .NET Debugging - Tess Ferrandez](https://www.youtube.com/watch?v=S-jiM07X3fs) - youtube video| slides [.Net debugging 2017](https://www.slideshare.net/slideshow/net-debugging-2017/71633740) |
| [Debugging NET Apps - Tess Ferrandez - NDC Oslo 2021](https://www.youtube.com/watch?v=5LTT8OfcnsM) - youtube video| slides [Debugging .NET apps](https://www.slideshare.net/slideshow/debugging-net-apps/251122931) |
| [CSI .NET – Debugging .NET Applications, by Tess Ferrandez-Norlander](https://www.youtube.com/watch?v=z2B8OruMT6s) - youtube video| slides [CSI .net core - debugging .net applications](https://www.slideshare.net/slideshow/csi-net-core-debugging-net-applications/248330523)|
| [.NET Debugging Techniques from a Real-World Investigation](https://www.youtube.com/watch?v=23E0JVmo9MM) - youtube video ||
| [Advanced .NET debugging - Tess Ferrandez-Norlander - NDC London 2022](https://www.youtube.com/watch?v=yA-b-V_9N_E) - youtube video ||
| [.NET Debugging Labs - Information and setup instructions ](https://www.tessferrandez.com/blog/2008/02/04/debugging-demos-setup-instructions.html) [archive.today](https://archive.ph/PThUn) | Tess Ferrandez's blog |
| [Debugging Managed Code Using the Windows Debugger](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/debugging-managed-code) [archive.today](https://archive.ph/PcbOw)| learn.microsoft.com, Article 09/28/2024 |
| [OutOfMemoryException and Pinning](https://learn.microsoft.com/en-us/archive/blogs/yunjin/outofmemoryexception-and-pinning) [archive.today](https://archive.ph/5eAXI) ||
| [Figure out variable lifetime using SOS](https://learn.microsoft.com/en-us/archive/blogs/yunjin/figure-out-variable-lifetime-using-sos) [archive.today](https://archive.ph/wXfos) ||
| [My application seems to hang. What do I do? – Part 1](https://devblogs.microsoft.com/dotnet/my-application-seems-to-hang-what-do-i-do-part-1/) [archive.today](https://archive.ph/AoH4f) | devblogs.microsoft.com, September 28th, 2006 |
| [My application seems to hang. What do I do? – Part 2](https://devblogs.microsoft.com/dotnet/my-application-seems-to-hang-what-do-i-do-part-2/) [archive.today](https://archive.ph/8nky9) | devblogs.microsoft.com, November 14th, 2006 |
| [Debugging .NET Core memory issues (on Linux) with dotnet dump](https://www.tessferrandez.com/blog/2021/03/18/debugging-a-netcore-memory-issue-with-dotnet-dump.html) [archive.today](https://archive.ph/y232F) | Tess Ferrandez's blog post, March 18, 2021 |
| [.NET Performance - Performance Diagnostics of .NET Applications Using ETW](https://learn.microsoft.com/en-us/archive/msdn-magazine/2010/december/msdn-magazine-net-performance-performance-diagnostics-of-net-applications-using-etw) [archive.org](http://web.archive.org/web/20230608164228/https://learn.microsoft.com/en-us/archive/msdn-magazine/2010/december/msdn-magazine-net-performance-performance-diagnostics-of-net-applications-using-etw) [archive.today](https://archive.ph/RqIyN) | MSDN Magazine December 2010, Volume 25 Number 12 |
| [Work flow of diagnosing memory performance issues – Part 0](https://devblogs.microsoft.com/dotnet/work-flow-of-diagnosing-memory-performance-issues-part-0/) [archive.org](http://web.archive.org/web/20240608162551/https://devblogs.microsoft.com/dotnet/work-flow-of-diagnosing-memory-performance-issues-part-0/) [archive.today](https://archive.ph/5kiov) |  |
| [Work flow of diagnosing memory performance issues – Part 1](https://devblogs.microsoft.com/dotnet/work-flow-of-diagnosing-memory-performance-issues-part-1/) [archive.org](http://web.archive.org/web/20240608162553/https://devblogs.microsoft.com/dotnet/work-flow-of-diagnosing-memory-performance-issues-part-1/) [archive.today](https://archive.ph/mjBDX) |  |
| [Work flow of diagnosing memory performance issues – Part 2](https://devblogs.microsoft.com/dotnet/work-flow-of-diagnosing-memory-performance-issues-part-2/) [archive.org](http://web.archive.org/web/20240302132333/https://devblogs.microsoft.com/dotnet/work-flow-of-diagnosing-memory-performance-issues-part-2/) [archive.today](https://archive.ph/la94J) |  |




## CLR
| Name                                                                       | Description                                                                        |
|----------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| [CLR Generics and code sharing](https://learn.microsoft.com/en-us/archive/blogs/joelpob/clr-generics-and-code-sharing) [archive.today](https://archive.ph/qZMt4) ||
| [CLR Inside Out - Memory Usage Auditing For .NET Applications](https://learn.microsoft.com/en-us/archive/msdn-magazine/2009/june/memory-usage-auditing-for-net-applications) [archive.today](https://archive.ph/MHEYO)| learn.microsoft.com, Article 08/14/2015|
| [.NET Framework Internals: How the CLR Creates Runtime Objects](https://learn.microsoft.com/en-us/archive/msdn-magazine/2005/may/net-framework-internals-how-the-clr-creates-runtime-objects) [archive.today](https://archive.ph/HiIa4) | MSDN Magazine Issues  2005  May |

## MISC
| Name                                                                       | Description                                                                        |
|----------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| [How the Clipboard Works, Part 1](https://burrough.org/archives/284) [archive.org](http://web.archive.org/web/20240303100349/https://burrough.org/archives/284) [archive.today](https://archive.ph/yuzLz) | This is an archive post of content written for the NTDebugging Blog on MSDN |
