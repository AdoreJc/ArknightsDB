# PauseEffectWithAnimation

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _finishIfPause`

- `Boolean _noPauseWhenValid`


## Methods

- `Void Update()`

- `Void _CheckPause()`

- `Void <>xLuaBaseProxy_OnPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class PauseEffectWithAnimation : Behaviour
{
	private List`1 _validAnimation; // 0x20
	private Boolean _finishIfPause; // 0x28
	private List`1 _invalidAnimation; // 0x30
	private Boolean _noPauseWhenValid; // 0x38
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__CheckPause; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2006424 VA: 0x759461e424
	public override Void OnPlay() { }
	// RVA: 0x2006498 VA: 0x759461e498
	private Void Update() { }
	// RVA: 0x2006500 VA: 0x759461e500
	private Void _CheckPause() { }
	// RVA: 0x200675c VA: 0x759461e75c
	public Void .ctor() { }
	// RVA: 0x20067c8 VA: 0x759461e7c8
	private Void <>xLuaBaseProxy_OnPlay() { }
}
```