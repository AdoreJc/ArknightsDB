# FileDownloader

**Namespace:** `Torappu.Network`


## Fields

- `Boolean m_isDispose`

- `Boolean m_isInterrupting`

- `Boolean allowProfile`


## Methods

- `Void DownloadFile(Options)`

- `Void Dispose()`

- `CancelletionInfo InterruptAll()`

- `Void _TryStartDownload(Options)`

- `Void _CheckPendingTasks(DownloadProcHandler)`

- `CancelletionInfo _CancelAllTasks()`

- `Void _StartDownloadTask(Options)`

- `IEnumerator _DownloadFileTask(DownloadTaskInput)`

- `IEnumerator _DownloadFile(DownloadTaskInput)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Network
public class FileDownloader : IDisposable
{
	private const Int32 MAX_CONNECTION_NUM; // 0x0
	private const Int32 CONNECTION_TIMEOUT; // 0x0
	private const Single CLIENT_PAUSE_THRESHOLD; // 0x0
	private Boolean m_isDispose; // 0x10
	private Boolean m_isInterrupting; // 0x11
	public Boolean allowProfile; // 0x12
	private List`1 m_downloadingTasks; // 0x18
	private Queue`1 m_pendingTasks; // 0x20


	// RVA: 0x67ac5a8 VA: 0x7598dc45a8
	public Void .ctor() { }
	// RVA: 0x67ac680 VA: 0x7598dc4680
	public Void DownloadFile(Options options) { }
	// RVA: 0x67ac7a0 VA: 0x7598dc47a0
	public Void Dispose() { }
	// RVA: 0x67ac8a4 VA: 0x7598dc48a4
	public CancelletionInfo InterruptAll() { }
	// RVA: 0x67ac6bc VA: 0x7598dc46bc
	private Void _TryStartDownload(Options options) { }
	// RVA: 0x67acb68 VA: 0x7598dc4b68
	private Void _CheckPendingTasks(DownloadProcHandler handler) { }
	// RVA: 0x67ac8b8 VA: 0x7598dc48b8
	private CancelletionInfo _CancelAllTasks() { }
	// RVA: 0x67ac9dc VA: 0x7598dc49dc
	private Void _StartDownloadTask(Options options) { }
	// RVA: 0x67accdc VA: 0x7598dc4cdc
	private IEnumerator _DownloadFileTask(DownloadTaskInput input) { }
	// RVA: 0x67acd94 VA: 0x7598dc4d94
	private IEnumerator _DownloadFile(DownloadTaskInput input) { }
}
```