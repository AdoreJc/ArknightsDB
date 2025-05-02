# FtpMethodInfo

**Namespace:** `System.Net`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class FtpMethodInfo
{
	internal String Method; // 0x10
	internal FtpOperation Operation; // 0x18
	internal FtpMethodFlags Flags; // 0x1c
	internal String HttpCommand; // 0x20
	private static readonly FtpMethodInfo[] s_knownMethodInfo; // 0x0

	internal Boolean IsCommandOnly { get; }
	internal Boolean IsUpload { get; }
	internal Boolean IsDownload { get; }
	internal Boolean ShouldParseForResponseUri { get; }

	// RVA: 0x6421184 VA: 0x7598a39184
	internal Void .ctor(String method, FtpOperation operation, FtpMethodFlags flags, String httpCommand) { }
	// RVA: 0x641ed28 VA: 0x7598a36d28
	internal Boolean HasFlag(FtpMethodFlags flags) { }
	// RVA: 0x641ef28 VA: 0x7598a36f28
	internal Boolean get_IsCommandOnly() { }
	// RVA: 0x641fd58 VA: 0x7598a37d58
	internal Boolean get_IsUpload() { }
	// RVA: 0x641fd64 VA: 0x7598a37d64
	internal Boolean get_IsDownload() { }
	// RVA: 0x641d424 VA: 0x7598a35424
	internal Boolean get_ShouldParseForResponseUri() { }
	// RVA: 0x64211dc VA: 0x7598a391dc
	internal static FtpMethodInfo GetMethodInfo(String method) { }
	// RVA: 0x6421340 VA: 0x7598a39340
	private static Void .cctor() { }
}
```