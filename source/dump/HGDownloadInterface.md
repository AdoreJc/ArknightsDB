# HGDownloadInterface

**Namespace:** ` `


## Fields

- `UnzipHandler m_unzipHandler`

- `TaskHandler m_task`

- `InternalState m_state`


## Methods

- `Void _CreateEmptyTaskAndApply()`

- `UnzipError _CreateCurrentUnzipError(HGRetCodeType, Int32)`

- `String _CreateErrorAlertFromCode(HGRetCodeType, Int32)`

- `Void _OnHGDownloadFinish()`

- `Void _OnHGError(HGRetCodeType, Int32)`

- `Void _OnHGDownloadPaused(PauseReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class HGDownloadInterface : DownloadInterface
{
	private UnzipHandler m_unzipHandler; // 0x38
	private TaskHandler m_task; // 0x40
	private InternalState m_state; // 0x48


	// RVA: 0x37384f8 VA: 0x7595d504f8
	private Void .ctor(DownloadOptions options) { }
	// RVA: 0x37385f0 VA: 0x7595d505f0
	public static HGDownloadInterface DownloadInterfaceOnly_Create(DownloadOptions options) { }
	// RVA: 0x3730bd0 VA: 0x7595d48bd0
	public static Void CleanWorkspaceIfInited() { }
	// RVA: 0x3738678 VA: 0x7595d50678
	public override Int64 CalculateTotalDownloadSize(String versionId, IList`1 updateResList) { }
	// RVA: 0x3738be8 VA: 0x7595d50be8
	public override Void ClearUnzipThread() { }
	// RVA: 0x3738bec VA: 0x7595d50bec
	protected override Void OnDispose() { }
	// RVA: 0x3738c18 VA: 0x7595d50c18
	public override Void InterruptAllDownloading() { }
	// RVA: 0x3738c38 VA: 0x7595d50c38
	public override Void StartDownload(DownloadParam param) { }
	// RVA: 0x3738e94 VA: 0x7595d50e94
	public override Void Tick() { }
	// RVA: 0x3738f0c VA: 0x7595d50f0c
	public override IEnumerator WaitForDownloadingStop() { }
	// RVA: 0x3738f94 VA: 0x7595d50f94
	public override IEnumerator WaitForInitFinish() { }
	// RVA: 0x373901c VA: 0x7595d5101c
	public override IUnzipInterface CreateCurrentUnzipInterface() { }
	// RVA: 0x37390d8 VA: 0x7595d510d8
	public override Void EnableMobileData() { }
	// RVA: 0x373878c VA: 0x7595d5078c
	private static List`1 _ConvertToHGFiles(String versionId, IList`1 abInfoList) { }
	// RVA: 0x3738e3c VA: 0x7595d50e3c
	private Void _CreateEmptyTaskAndApply() { }
	// RVA: 0x373911c VA: 0x7595d5111c
	private UnzipError _CreateCurrentUnzipError(HGRetCodeType type, Int32 errorCode) { }
	// RVA: 0x37392a0 VA: 0x7595d512a0
	private String _CreateErrorAlertFromCode(HGRetCodeType type, Int32 errorCode) { }
	// RVA: 0x37390f8 VA: 0x7595d510f8
	private Void _OnHGDownloadFinish() { }
	// RVA: 0x37393d0 VA: 0x7595d513d0
	private Void _OnHGError(HGRetCodeType codeType, Int32 errorCode) { }
	// RVA: 0x3739510 VA: 0x7595d51510
	private Void _OnHGDownloadPaused(PauseReason reason) { }
}
```