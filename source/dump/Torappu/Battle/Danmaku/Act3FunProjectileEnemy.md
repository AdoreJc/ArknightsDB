# Act3FunProjectileEnemy

**Namespace:** `Torappu.Battle.Danmaku`


## Fields

- `Int32 _overridePreloadCnt`


## Properties

- `FP distToAircraft`


## Methods

- `FP get_distToAircraft()`

- `Int32 <>xLuaBaseProxy_get_initState()`

- `Boolean <>xLuaBaseProxy_get_disableUIUnitHud()`

- `Int32 <>xLuaBaseProxy_get_preloadCnt()`

- `FP <>xLuaBaseProxy_get_hatred()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Danmaku
public class Act3FunProjectileEnemy : FixedDirectionEnemy
{
	private Int32 _overridePreloadCnt; // 0x4c0
	private static DelegateBridge __Hotfix0_get_initState; // 0x0
	private static DelegateBridge __Hotfix0_get_disableUIUnitHud; // 0x8
	private static DelegateBridge __Hotfix0_get_preloadCnt; // 0x10
	private static DelegateBridge __Hotfix0_get_hatred; // 0x18
	private static DelegateBridge __Hotfix0_get_distToAircraft; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override Int32 initState { get; }
	public override Boolean disableUIUnitHud { get; }
	public override Int32 preloadCnt { get; }
	public override FP hatred { get; }
	public FP distToAircraft { get; }

	// RVA: 0x1d2f3cc VA: 0x75943473cc
	protected override Int32 get_initState() { }
	// RVA: 0x1d2f434 VA: 0x7594347434
	public override Boolean get_disableUIUnitHud() { }
	// RVA: 0x1d2f49c VA: 0x759434749c
	public override Int32 get_preloadCnt() { }
	// RVA: 0x1d2f520 VA: 0x7594347520
	public override FP get_hatred() { }
	// RVA: 0x1d2f6dc VA: 0x75943476dc
	public FP get_distToAircraft() { }
	// RVA: 0x1d2f954 VA: 0x7594347954
	public Void .ctor() { }
	// RVA: 0x1d2f9c4 VA: 0x75943479c4
	private Int32 <>xLuaBaseProxy_get_initState() { }
	// RVA: 0x1d2f9cc VA: 0x75943479cc
	private Boolean <>xLuaBaseProxy_get_disableUIUnitHud() { }
	// RVA: 0x1d2f9d4 VA: 0x75943479d4
	private Int32 <>xLuaBaseProxy_get_preloadCnt() { }
	// RVA: 0x1d2f9dc VA: 0x75943479dc
	private FP <>xLuaBaseProxy_get_hatred() { }
}
```