# ActMultiV3MatchState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Single _openMatchPageDelay`

- `Tween m_delayTween`

- `String m_actId`


## Methods

- `Void _OpenMatchPage()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MatchState : State
{
	private Single _openMatchPageDelay; // 0x50
	private Tween m_delayTween; // 0x58
	private String m_actId; // 0x60
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__OpenMatchPage; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30f2408 VA: 0x759570a408
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30f246c VA: 0x759570a46c
	protected override Void OnEnter() { }
	// RVA: 0x30f26a0 VA: 0x759570a6a0
	private Void _OpenMatchPage() { }
	// RVA: 0x30f2788 VA: 0x759570a788
	public Void .ctor() { }
	// RVA: 0x30f27f8 VA: 0x759570a7f8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```