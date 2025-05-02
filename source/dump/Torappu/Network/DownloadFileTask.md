# DownloadFileTask

**Namespace:** `Torappu.Network`


## Fields

- `FileStream m_fstream`

- `HTTPRequest m_request`

- `Boolean m_isError`

- `Boolean m_isFinished`

- `Boolean m_isDisposed`

- `Int64 m_downloadSize`

- `Options m_options`

- `Int64 <targetFileSize>k__BackingField`

- `String <errorMessage>k__BackingField`


## Properties

- `Int64 downloadSize`

- `Int64 targetFileSize`

- `Boolean isFinished`

- `Boolean isError`

- `String errorMessage`

- `Boolean isConnectionTimeout`


## Methods

- `Int64 get_downloadSize()`

- `Int64 get_targetFileSize()`

- `Void set_targetFileSize(Int64)`

- `Boolean get_isFinished()`

- `Boolean get_isError()`

- `String get_errorMessage()`

- `Void set_errorMessage(String)`

- `Boolean get_isConnectionTimeout()`

- `Void Abort()`

- `Void _OnResponseFragments(HTTPRequest, HTTPResponse)`

- `Void Dispose()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Network
public class DownloadFileTask : IDisposable
{
	private const Int32 DOWNLOAD_FRAGMENT_SIZE; // 0x0
	private const Int32 DEFAULT_CON_TIMEOUT; // 0x0
	private FileStream m_fstream; // 0x10
	private HTTPRequest m_request; // 0x18
	private Boolean m_isError; // 0x20
	private Boolean m_isFinished; // 0x21
	private Boolean m_isDisposed; // 0x22
	private Int64 m_downloadSize; // 0x28
	private Options m_options; // 0x30
	private Int64 <targetFileSize>k__BackingField; // 0x58
	private String <errorMessage>k__BackingField; // 0x60

	public Int64 downloadSize { get; }
	public Int64 targetFileSize { get; set; }
	public Boolean isFinished { get; }
	public Boolean isError { get; }
	public String errorMessage { get; set; }
	public Boolean isConnectionTimeout { get; }

	// RVA: 0x67ab890 VA: 0x7598dc3890
	public static DownloadFileTask StartDownloadTask(Options options) { }
	// RVA: 0x67abcf0 VA: 0x7598dc3cf0
	public Int64 get_downloadSize() { }
	// RVA: 0x67abcf8 VA: 0x7598dc3cf8
	public Int64 get_targetFileSize() { }
	// RVA: 0x67abd00 VA: 0x7598dc3d00
	private Void set_targetFileSize(Int64 value) { }
	// RVA: 0x67abd08 VA: 0x7598dc3d08
	public Boolean get_isFinished() { }
	// RVA: 0x67abd10 VA: 0x7598dc3d10
	public Boolean get_isError() { }
	// RVA: 0x67abd18 VA: 0x7598dc3d18
	public String get_errorMessage() { }
	// RVA: 0x67abd20 VA: 0x7598dc3d20
	private Void set_errorMessage(String value) { }
	// RVA: 0x67abd28 VA: 0x7598dc3d28
	public Boolean get_isConnectionTimeout() { }
	// RVA: 0x67abd48 VA: 0x7598dc3d48
	public Void Abort() { }
	// RVA: 0x67abd84 VA: 0x7598dc3d84
	private Void _OnResponseFragments(HTTPRequest request, HTTPResponse response) { }
	// RVA: 0x67abfe4 VA: 0x7598dc3fe4
	public Void Dispose() { }
	// RVA: 0x67abd58 VA: 0x7598dc3d58
	private static Void _TryAbortRequest(HTTPRequest request) { }
	// RVA: 0x67abce8 VA: 0x7598dc3ce8
	public Void .ctor() { }
}
```