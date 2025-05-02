# FifthAnnivExploreMapEntryState

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `GameObject _mapEntryGo`

- `UIAnimationLocation _animEntry`

- `UIAnimationLocation _animEntrySideBar`

- `FifthAnnivExploreMapEffect _animMapEffect`

- `Tween m_enterTween`


## Methods

- `Void _OnJumpFromGroupChooseState(IStateBean)`

- `Void <_OnJumpFromGroupChooseState>b__8_0()`

- `Void <_OnJumpFromGroupChooseState>b__8_1()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMapEntryState : PopupFadeState
{
	private GameObject _mapEntryGo; // 0x70
	private UIAnimationLocation _animEntry; // 0x78
	private UIAnimationLocation _animEntrySideBar; // 0x88
	private FifthAnnivExploreMapEffect _animMapEffect; // 0x98
	private Tween m_enterTween; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x10
	private static DelegateBridge __Hotfix0__OnJumpFromGroupChooseState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x291fff0 VA: 0x7594f37ff0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2920054 VA: 0x7594f38054
	protected override Void OnEnter() { }
	// RVA: 0x2920124 VA: 0x7594f38124
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x292029c VA: 0x7594f3829c
	private Void _OnJumpFromGroupChooseState(IStateBean stateBean) { }
	// RVA: 0x292055c VA: 0x7594f3855c
	public Void .ctor() { }
	// RVA: 0x29205cc VA: 0x7594f385cc
	private Void <_OnJumpFromGroupChooseState>b__8_0() { }
	// RVA: 0x29206d0 VA: 0x7594f386d0
	private Void <_OnJumpFromGroupChooseState>b__8_1() { }
	// RVA: 0x2920700 VA: 0x7594f38700
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2920708 VA: 0x7594f38708
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```