# ClimbTowerEntryMissionState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerEntryMissionGroupView _missionGroupView`

- `ClimbTowerEntryMissionDockerView _dockerView`

- `Transform _topContainer`

- `ClimbTowerEntryMissionStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnMissionItemClicked(String)`

- `Void <_InitIfNot>b__8_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryMissionState : PopupFadeState, IHotfixable
{
	private ClimbTowerEntryMissionGroupView _missionGroupView; // 0x70
	private ClimbTowerEntryMissionDockerView _dockerView; // 0x78
	private Transform _topContainer; // 0x80
	private ClimbTowerEntryMissionStateBean m_stateBean; // 0x88
	private Boolean m_hasInited; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnMissionItemClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2ca1b90 VA: 0x75952b9b90
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ca1bf8 VA: 0x75952b9bf8
	protected override Void OnEnter() { }
	// RVA: 0x2ca1e94 VA: 0x75952b9e94
	protected override Void OnResume() { }
	// RVA: 0x2ca1cd4 VA: 0x75952b9cd4
	private Void _InitIfNot() { }
	// RVA: 0x2ca1f78 VA: 0x75952b9f78
	private Void _OnMissionItemClicked(String missionId) { }
	// RVA: 0x2ca22f0 VA: 0x75952ba2f0
	public Void .ctor() { }
	// RVA: 0x2ca244c VA: 0x75952ba44c
	private Void <_InitIfNot>b__8_0() { }
	// RVA: 0x2ca252c VA: 0x75952ba52c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ca2534 VA: 0x75952ba534
	private Void <>xLuaBaseProxy_OnResume() { }
}
```