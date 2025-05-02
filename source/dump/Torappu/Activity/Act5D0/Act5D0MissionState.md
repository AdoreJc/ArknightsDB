# Act5D0MissionState

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `Act5D0MissionStateBean _stateBean`

- `Act5D0MissionView _view`

- `Transform _topMenuContainer`

- `CommonTopMenu m_topMenu`

- `String m_cacheTransId`


## Methods

- `Void InitTopMenu()`

- `Void <InitTopMenu>b__7_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0MissionState : PopupFadeState
{
	private Act5D0MissionStateBean _stateBean; // 0x70
	private Act5D0MissionView _view; // 0x78
	private Transform _topMenuContainer; // 0x80
	private CommonTopMenu m_topMenu; // 0x88
	private String m_cacheTransId; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_InitTopMenu; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31be6b0 VA: 0x75957d66b0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31be718 VA: 0x75957d6718
	protected override Void OnEnter() { }
	// RVA: 0x31beaa8 VA: 0x75957d6aa8
	private Void InitTopMenu() { }
	// RVA: 0x31bec78 VA: 0x75957d6c78
	public Void .ctor() { }
	// RVA: 0x31bed20 VA: 0x75957d6d20
	private Void <InitTopMenu>b__7_0() { }
	// RVA: 0x31bed30 VA: 0x75957d6d30
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```