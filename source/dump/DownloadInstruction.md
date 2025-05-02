# DownloadInstruction

**Namespace:** ` `


## Fields

- `Boolean m_isFinished`

- `Boolean m_isAboutToFinish`

- `HotUpdateWorkflow m_workflow`

- `HotUpdateViewController m_viewCtrl`

- `HotUpdater m_updater`

- `RetryPolicy m_retryPolicy`

- `DownloadPartEnum m_partEnum`

- `ENode m_nodeType`

- `DownloadProgress m_downloadProg`

- `SimpleProgress m_unzipProg`

- `ResRecoverProgress m_resRecoverProg`


## Methods

- `Void Dispose()`

- `Void _DisposeProgress()`

- `Boolean _AchieveFinishLock()`

- `Void _HandleErrorUpdateState(UpdateState, UpdateState)`

- `Void _RetryNodeDelayed(ENode, Single)`

- `Void _RetryNode(ENode)`

- `Void _OnHotUpdateStateChange(UpdateState, UpdateState)`

- `Void _OnDownloadStart()`

- `Void _OnUnZipStart()`

- `Void _OnDownloadProgress(Int64, Int64)`

- `Void _OnUnzipProgress(Single)`

- `Void _OnRecoverPersistResInfoPrg(Int32, Int32)`

- `Void <_HandleErrorUpdateState>b__18_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DownloadInstruction : CustomYieldInstruction, IDisposable
{
	private Boolean m_isFinished; // 0x10
	private Boolean m_isAboutToFinish; // 0x11
	private HotUpdateWorkflow m_workflow; // 0x18
	private HotUpdateViewController m_viewCtrl; // 0x20
	private HotUpdater m_updater; // 0x28
	private RetryPolicy m_retryPolicy; // 0x30
	private DownloadPartEnum m_partEnum; // 0x38
	private ENode m_nodeType; // 0x3c
	private DownloadProgress m_downloadProg; // 0x40
	private SimpleProgress m_unzipProg; // 0x48
	private ResRecoverProgress m_resRecoverProg; // 0x50

	public override Boolean keepWaiting { get; }

	// RVA: 0x27c199c VA: 0x7594dd999c
	public override Boolean get_keepWaiting() { }
	// RVA: 0x27c19ac VA: 0x7594dd99ac
	public Void Dispose() { }
	// RVA: 0x27c1a50 VA: 0x7594dd9a50
	private Void _DisposeProgress() { }
	// RVA: 0x27c1b74 VA: 0x7594dd9b74
	public Void .ctor(HotUpdateViewController viewCtrl, HotUpdateWorkflow workflow, ENode nodeType) { }
	// RVA: 0x27c2020 VA: 0x7594dda020
	private Boolean _AchieveFinishLock() { }
	// RVA: 0x27c2048 VA: 0x7594dda048
	private Void _HandleErrorUpdateState(UpdateState prevState, UpdateState curState) { }
	// RVA: 0x27c2180 VA: 0x7594dda180
	private Void _RetryNodeDelayed(ENode node, Single delay) { }
	// RVA: 0x27c2280 VA: 0x7594dda280
	private Void _RetryNode(ENode node) { }
	// RVA: 0x27c22b4 VA: 0x7594dda2b4
	private Void _OnHotUpdateStateChange(UpdateState prevState, UpdateState curState) { }
	// RVA: 0x27c23d4 VA: 0x7594dda3d4
	private Void _OnDownloadStart() { }
	// RVA: 0x27c2424 VA: 0x7594dda424
	private Void _OnUnZipStart() { }
	// RVA: 0x27c2500 VA: 0x7594dda500
	private Void _OnDownloadProgress(Int64 curSize, Int64 totalSize) { }
	// RVA: 0x27c25b8 VA: 0x7594dda5b8
	private Void _OnUnzipProgress(Single progress) { }
	// RVA: 0x27c2640 VA: 0x7594dda640
	private Void _OnRecoverPersistResInfoPrg(Int32 curCount, Int32 totalCount) { }
	// RVA: 0x27c2708 VA: 0x7594dda708
	private Void <_HandleErrorUpdateState>b__18_0() { }
}
```