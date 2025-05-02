# RoguelikeIndexState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Boolean m_inited`

- `RoguelikeMenuAdapter m_menuAdapter`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeIndexState : State
{
	private Boolean m_inited; // 0x50
	private RoguelikeMenuAdapter m_menuAdapter; // 0x58
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnPause; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2a07b48 VA: 0x759501fb48
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a07bac VA: 0x759501fbac
	protected override Void OnEnter() { }
	// RVA: 0x2a07dac VA: 0x759501fdac
	protected override Void OnResume() { }
	// RVA: 0x2a07e30 VA: 0x759501fe30
	protected override Void OnPause() { }
	// RVA: 0x2a07d10 VA: 0x759501fd10
	private Void _InitIfNot() { }
	// RVA: 0x2a07eb4 VA: 0x759501feb4
	public Void .ctor() { }
	// RVA: 0x2a07f24 VA: 0x759501ff24
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2a07f2c VA: 0x759501ff2c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2a07f34 VA: 0x759501ff34
	private Void <>xLuaBaseProxy_OnPause() { }
}
```