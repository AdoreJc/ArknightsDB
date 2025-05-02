# ZipUtils

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class ZipUtils : IHotfixable
{
	private const Int32 BUFFER_LENGTH; // 0x0
	private const String DEFAULT_ENTRY; // 0x0
	private static __XLua_Gen_Delegate87 __Hotfix0_Decompress; // 0x0
	private static __XLua_Gen_Delegate87 __Hotfix1_Decompress; // 0x8
	private static __XLua_Gen_Delegate88 __Hotfix2_Decompress; // 0x10
	private static __XLua_Gen_Delegate88 __Hotfix0_Compress; // 0x18
	private static __XLua_Gen_Delegate88 __Hotfix0_CompressToZipBytes; // 0x20
	private static __XLua_Gen_Delegate88 __Hotfix0_DecompressFromZipBytes; // 0x28
	private static __XLua_Gen_Delegate89 __Hotfix0_CompressStrToBase64; // 0x30
	private static __XLua_Gen_Delegate89 __Hotfix0_DecompressStrFromBase64; // 0x38
	private static __XLua_Gen_Delegate88 __Hotfix0_DecompressGZip; // 0x40
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x48


	// RVA: 0x6778cfc VA: 0x7598d90cfc
	private static Void .cctor() { }
	// RVA: 0x6778dac VA: 0x7598d90dac
	public static Void Decompress(String outputFolder, String zipFilePath, UnzipThreadContext context) { }
	// RVA: 0x6779044 VA: 0x7598d91044
	public static Void Decompress(String outputFolder, Stream stream, UnzipThreadContext context) { }
	// RVA: 0x67796c8 VA: 0x7598d916c8
	public static Int32 Decompress(Stream input, out Byte[] outBytes) { }
	// RVA: 0x6779b40 VA: 0x7598d91b40
	public static Int32 Compress(Stream input, out Byte[] outBytes) { }
	// RVA: 0x677a04c VA: 0x7598d9204c
	public static Int32 CompressToZipBytes(Byte[] input, out Byte[] outBytes) { }
	// RVA: 0x677a388 VA: 0x7598d92388
	public static Int32 DecompressFromZipBytes(Byte[] input, out Byte[] outBytes) { }
	// RVA: 0x677a6b8 VA: 0x7598d926b8
	public static String CompressStrToBase64(String src) { }
	// RVA: 0x677a7d0 VA: 0x7598d927d0
	public static String DecompressStrFromBase64(String src) { }
	// RVA: 0x677a8e8 VA: 0x7598d928e8
	public static Int32 DecompressGZip(Byte[] inBytes, out Byte[] outBytes) { }
	// RVA: 0x677ae60 VA: 0x7598d92e60
	public Void .ctor() { }
}
```