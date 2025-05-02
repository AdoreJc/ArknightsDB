# DownloadProcHandler

**Namespace:** ` `


## Fields

- `Boolean m_isContinue`

- `DownloadFileTask m_internalTask`

- `Int64 <downloadSize>k__BackingField`

- `DownloadState state`


## Properties

- `Int64 downloadSize`

- `Boolean isContinue`

- `Boolean isNotRunning`


## Methods

- `Int64 get_downloadSize()`

- `Void set_downloadSize(Int64)`

- `Boolean get_isContinue()`

- `Boolean get_isNotRunning()`

- `Void Cancel()`

- `Void FileDownloader_BindTask(DownloadFileTask)`

- `Boolean UpdateDownloadSize(Int64)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class DownloadProcHandler
{
	private Boolean m_isContinue; // 0x10
	private DownloadFileTask m_internalTask; // 0x18
	private Int64 <downloadSize>k__BackingField; // 0x20
	public DownloadState state; // 0x28

	public Int64 downloadSize { get; set; }
	public Boolean isContinue { get; }
	public Boolean isNotRunning { get; }

	// RVA: 0x67ad228 VA: 0x7598dc5228
	public Int64 get_downloadSize() { }
	// RVA: 0x67ad230 VA: 0x7598dc5230
	private Void set_downloadSize(Int64 value) { }
	// RVA: 0x67ad238 VA: 0x7598dc5238
	public Boolean get_isContinue() { }
	// RVA: 0x67ad174 VA: 0x7598dc5174
	public Boolean get_isNotRunning() { }
	// RVA: 0x67ac870 VA: 0x7598dc4870
	public Void Cancel() { }
	// RVA: 0x67ad240 VA: 0x7598dc5240
	public Void FileDownloader_BindTask(DownloadFileTask task) { }
	// RVA: 0x67ad248 VA: 0x7598dc5248
	public Boolean UpdateDownloadSize(Int64 newSize) { }
	// RVA: 0x67acccc VA: 0x7598dc4ccc
	public Void .ctor() { }
}
```