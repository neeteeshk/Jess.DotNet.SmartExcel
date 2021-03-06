# Jess.DotNet.SmartExcel

> Excel 2.1 生成类库 —— 暂时仅支持biff2.1格式生成

[![Jess.DotNet.SmartExcel](https://img.shields.io/nuget/dt/Jess.DotNet.SmartExcel)](https://www.nuget.org/packages/Jess.DotNet.SmartExcel/) 

## RoadMap

* RtlCopyMemory调整为Buffer.MemoryCopy 【多系统支持】
    * https://docs.microsoft.com/zh-cn/dotnet/api/system.buffer.memorycopy?view=net-5.0


## 参考

### File

* [`[MS-XLS]-120120.pdf`](./docs/[MS-XLS]-120120.pdf)
    * Excel Binary File Format (.xls) Structure Specification
    * 97之后的版本说明
* [excelfileformat.pdf](./docs/excelfileformat.pdf)
    * Microsoft Excel File Format
    * Excel Versions 2, 3, 4, 5, 95, 97, 2000, XP, 2003

### URL

* [VB.NET生成Excel（Biff2.1） —— 灵感之源](https://www.cnblogs.com/unruledboy/archive/2004/07/07/22093.html)
    * [代码目录](./ref/VB/SmartExcelLib/)
* [C#版SmartExcel —— 鞠强](https://www.cnblogs.com/juqiang/archive/2004/07/08/22255.html)
    * 本库初始实现就是拷贝此地址代码实现

----

* [MICROSOFT EXCEL FILE FORMAT（BIFF2.1） 文件格式参考](https://www.cnblogs.com/shiningrise/archive/2007/06/23/793836.html)
* [Microsoft Excel 2.1 简介](https://winworldpc.com/product/microsoft-excel/2x)
    * [Microsoft Excel 2.1 (5.25)安装程序](./tools/Microsoft%20Excel%202.1%20(5.25).7z)
* [Excel Biff 二进制文件格式参考](https://docs.microsoft.com/en-us/openspecs/office_file_formats/ms-xls/cd03cb5f-ca02-4934-a391-bb674cb8aa06)
    * 仅包含97之后版本说明，但对于excel 2版本，可以参考
