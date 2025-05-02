# Act1LockStageController

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Act1LockMainProperty m_mainProperty`

- `TrackPointViewProperty m_milestoneTrackProperty`

- `TrackPointViewProperty m_missionTrackProperty`

- `Boolean m_isCustomInitFinish`


## Properties

- `Act1LockMainProperty mainProperty`

- `TrackPointViewProperty milestoneTrackProperty`

- `TrackPointViewProperty missionTrackProperty`


## Methods

- `Act1LockMainProperty get_mainProperty()`

- `TrackPointViewProperty get_milestoneTrackProperty()`

- `TrackPointViewProperty get_missionTrackProperty()`

- `Void RefreshMainInfo()`

- `IEnumerator _TryOpenMapPage(String)`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`

- `IEnumerator <>xLuaBaseProxy_LoadCoroutine()`

- `IEnumerator <>xLuaBaseProxy_GetReadySignalForStagePage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockStageController : ActivityStageController
{
	private Act1LockMainProperty m_mainProperty; // 0x60
	private TrackPointViewProperty m_milestoneTrackProperty; // 0x68
	private TrackPointViewProperty m_missionTrackProperty; // 0x70
	private Boolean m_isCustomInitFinish; // 0x78
	private static DelegateBridge __Hotfix0_get_mainProperty; // 0x0
	private static DelegateBridge __Hotfix0_get_milestoneTrackProperty; // 0x8
	private static DelegateBridge __Hotfix0_get_missionTrackProperty; // 0x10
	private static DelegateBridge __Hotfix0_RefreshMainInfo; // 0x18
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x20
	private static DelegateBridge __Hotfix0_LoadCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__TryOpenMapPage; // 0x30
	private static DelegateBridge __Hotfix0_GetReadySignalForStagePage; // 0x38
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Act1LockMainProperty mainProperty { get; }
	public TrackPointViewProperty milestoneTrackProperty { get; }
	public TrackPointViewProperty missionTrackProperty { get; }

	// RVA: 0x339b4ec VA: 0x75959b34ec
	public Act1LockMainProperty get_mainProperty() { }
	// RVA: 0x339b554 VA: 0x75959b3554
	public TrackPointViewProperty get_milestoneTrackProperty() { }
	// RVA: 0x339b5bc VA: 0x75959b35bc
	public TrackPointViewProperty get_missionTrackProperty() { }
	// RVA: 0x339b624 VA: 0x75959b3624
	public Void RefreshMainInfo() { }
	// RVA: 0x339b6b4 VA: 0x75959b36b4
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x339b764 VA: 0x75959b3764
	public override IEnumerator LoadCoroutine() { }
	// RVA: 0x339b838 VA: 0x75959b3838
	private IEnumerator _TryOpenMapPage(String stageId) { }
	// RVA: 0x339b930 VA: 0x75959b3930
	public override IEnumerator GetReadySignalForStagePage() { }
	// RVA: 0x339ba04 VA: 0x75959b3a04
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x339baa4 VA: 0x75959b3aa4
	public Void .ctor() { }
	// RVA: 0x339bbb8 VA: 0x75959b3bb8
	private IEnumerator <>n__0() { }
	// RVA: 0x339bbc0 VA: 0x75959b3bc0
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
	// RVA: 0x339bbf0 VA: 0x75959b3bf0
	private IEnumerator <>xLuaBaseProxy_LoadCoroutine() { }
	// RVA: 0x339bbf8 VA: 0x75959b3bf8
	private IEnumerator <>xLuaBaseProxy_GetReadySignalForStagePage() { }
}
```