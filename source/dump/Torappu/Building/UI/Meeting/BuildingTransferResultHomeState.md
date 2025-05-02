# BuildingTransferResultHomeState

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Image _blueBackground`

- `PrefabInstHolder _topMenuHolder`

- `Text _visitNumberLabel`

- `Text _socialPointLabel`

- `MeetingPeerAdapter _peerAdapter`

- `IMeetingSession m_currentSession`


## Methods

- `Void _InitTopMenu()`

- `Void SetupView()`

- `Void <_InitTopMenu>b__7_0(GameObject)`

- `Void <_InitTopMenu>b__7_1()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingTransferResultHomeState : State
{
	private Image _blueBackground; // 0x50
	private PrefabInstHolder _topMenuHolder; // 0x58
	private Text _visitNumberLabel; // 0x60
	private Text _socialPointLabel; // 0x68
	private MeetingPeerAdapter _peerAdapter; // 0x70
	private IMeetingSession m_currentSession; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_SetupView; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3df3d38 VA: 0x759640bd38
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3df3d9c VA: 0x759640bd9c
	private Void _InitTopMenu() { }
	// RVA: 0x3df3e60 VA: 0x759640be60
	protected override Void OnEnter() { }
	// RVA: 0x3df4294 VA: 0x759640c294
	protected override Void OnExit() { }
	// RVA: 0x3df3f7c VA: 0x759640bf7c
	private Void SetupView() { }
	// RVA: 0x3df4390 VA: 0x759640c390
	public Void .ctor() { }
	// RVA: 0x3df4400 VA: 0x759640c400
	private Void <_InitTopMenu>b__7_0(GameObject obj) { }
	// RVA: 0x3df44c4 VA: 0x759640c4c4
	private Void <_InitTopMenu>b__7_1() { }
	// RVA: 0x3df44e4 VA: 0x759640c4e4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3df44ec VA: 0x759640c4ec
	private Void <>xLuaBaseProxy_OnExit() { }
}
```