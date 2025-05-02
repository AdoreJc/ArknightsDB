# SecScanInfo

**Namespace:** ` `


## Fields

- `Int32 sec_scan_status`

- `UInt16 scan_data_len`

- `IntPtr scan_data`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
private class SecScanInfo
{
	public Int32 sec_scan_status; // 0x10
	public UInt16 scan_data_len; // 0x14
	public IntPtr scan_data; // 0x18


	// RVA: 0x66bc704 VA: 0x7598cd4704
	public Void .ctor() { }
}
```