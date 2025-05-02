# FlyToPredefinedLocation

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `PredefinedLocation _location`

- `Single _duration`

- `Ease _easeType`

- `Boolean _isIndependentUpdate`

- `Boolean _inversStartEnd`

- `Tween m_tween`


## Methods

- `Void <OnPlay>b__6_0()`

- `Void <OnPlay>b__6_1()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class FlyToPredefinedLocation : Behaviour
{
	private PredefinedLocation _location; // 0x20
	private Single _duration; // 0x24
	private Ease _easeType; // 0x28
	private Boolean _isIndependentUpdate; // 0x2c
	private Boolean _inversStartEnd; // 0x2d
	private Tween m_tween; // 0x30
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1ffb3a0 VA: 0x75946133a0
	public override Void OnPlay() { }
	// RVA: 0x1ffb6bc VA: 0x75946136bc
	public override Void OnRecycle() { }
	// RVA: 0x1ffb7f4 VA: 0x75946137f4
	public Void .ctor() { }
	// RVA: 0x1ffb86c VA: 0x759461386c
	private Void <OnPlay>b__6_0() { }
	// RVA: 0x1ffb88c VA: 0x759461388c
	private Void <OnPlay>b__6_1() { }
	// RVA: 0x1ffb8ac VA: 0x75946138ac
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ffb8b0 VA: 0x75946138b0
	private Void <>xLuaBaseProxy_OnRecycle() { }
}
```