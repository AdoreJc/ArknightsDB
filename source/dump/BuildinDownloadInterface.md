# BuildinDownloadInterface

**Namespace:** ` `


## Fields

- `Boolean m_isDisposed`

- `Int64 m_curResSize`

- `Int64 m_totalResSize`

- `UnzipTaskThread m_unzipThread`

- `Int32 m_downloadFinishCount`

- `FileDownloader m_downloader`

- `CancelletionInfo m_lastStopDownloadInfo`

- `String m_internalResCacheDir`


## Properties

- `String resCacheDir`


## Methods

- `String get_resCacheDir()`

- `Options _GenerateUnzipOptions()`

- `Void _OnABDownloadSizeChange(Int32, Int64)`

- `Boolean _OnABDownloadFinish(Boolean, Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BuildinDownloadInterface : DownloadInterface
{
	private Boolean m_isDisposed; // 0x38
	private Int64 m_curResSize; // 0x40
	private Int64 m_totalResSize; // 0x48
	private UnzipTaskThread m_unzipThread; // 0x50
	private List`1 m_filesToDownload; // 0x58
	private Int32 m_downloadFinishCount; // 0x60
	private Queue`1 m_downloadMsgQueue; // 0x68
	private FileDownloader m_downloader; // 0x70
	private CancelletionInfo m_lastStopDownloadInfo; // 0x78
	private String m_internalResCacheDir; // 0x80

	protected String resCacheDir { get; }

	// RVA: 0x37398bc VA: 0x7595d518bc
	protected String get_resCacheDir() { }
	// RVA: 0x37398ec VA: 0x7595d518ec
	private Void .ctor(DownloadOptions options) { }
	// RVA: 0x3739800 VA: 0x7595d51800
	public static BuildinDownloadInterface DownloadInterfaceOnly_Create(DownloadOptions options) { }
	// RVA: 0x3739a40 VA: 0x7595d51a40
	public override Void ClearUnzipThread() { }
	// RVA: 0x3739a74 VA: 0x7595d51a74
	public override Int64 CalculateTotalDownloadSize(String versionId, IList`1 updateResList) { }
	// RVA: 0x3739bfc VA: 0x7595d51bfc
	public override Void InterruptAllDownloading() { }
	// RVA: 0x3739cac VA: 0x7595d51cac
	public override IEnumerator WaitForInitFinish() { }
	// RVA: 0x3739d0c VA: 0x7595d51d0c
	public override IEnumerator WaitForDownloadingStop() { }
	// RVA: 0x3739d80 VA: 0x7595d51d80
	protected override Void OnDispose() { }
	// RVA: 0x3739db8 VA: 0x7595d51db8
	public override IUnzipInterface CreateCurrentUnzipInterface() { }
	// RVA: 0x3739e1c VA: 0x7595d51e1c
	public override Void Tick() { }
	// RVA: 0x373a194 VA: 0x7595d52194
	public override Void StartDownload(DownloadParam param) { }
	// RVA: 0x373a828 VA: 0x7595d52828
	public override Void EnableMobileData() { }
	// RVA: 0x373a7d0 VA: 0x7595d527d0
	private Options _GenerateUnzipOptions() { }
	// RVA: 0x3739fc0 VA: 0x7595d51fc0
	private Void _OnABDownloadSizeChange(Int32 index, Int64 size) { }
	// RVA: 0x373a068 VA: 0x7595d52068
	private Boolean _OnABDownloadFinish(Boolean isSuc, Options options) { }
}
```