# Act4D0StoryState

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `Act4D0StoryStateBean _stateBean`

- `Act4D0StoryView _view`

- `Int32 m_currentSelect`


## Methods

- `Boolean _NeedScroll()`

- `Void _OnItemClickCallBack(Int32)`

- `Void _OnJumpToDetailState(Act4D0StoryDetailStateBean)`

- `Void <RegisterToDataListener>b__7_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0StoryState : PopupFadeState
{
	private Act4D0StoryStateBean _stateBean; // 0x70
	private Act4D0StoryView _view; // 0x78
	private Int32 m_currentSelect; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__NeedScroll; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClickCallBack; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToDetailState; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31df014 VA: 0x75957f7014
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31df07c VA: 0x75957f707c
	protected override Void OnEnter() { }
	// RVA: 0x31df4e8 VA: 0x75957f74e8
	private Boolean _NeedScroll() { }
	// RVA: 0x31df8a8 VA: 0x75957f78a8
	private Void _OnItemClickCallBack(Int32 index) { }
	// RVA: 0x31df9cc VA: 0x75957f79cc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x31dfb44 VA: 0x75957f7b44
	private Void _OnJumpToDetailState(Act4D0StoryDetailStateBean bean) { }
	// RVA: 0x31dfcd4 VA: 0x75957f7cd4
	public Void .ctor() { }
	// RVA: 0x31dfd44 VA: 0x75957f7d44
	private Void <RegisterToDataListener>b__7_0(IStateBean stateBean) { }
	// RVA: 0x31dfdc4 VA: 0x75957f7dc4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x31dfdcc VA: 0x75957f7dcc
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```