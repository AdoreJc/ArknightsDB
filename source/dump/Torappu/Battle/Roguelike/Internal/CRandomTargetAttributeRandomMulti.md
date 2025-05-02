# CRandomTargetAttributeRandomMulti

**Namespace:** `Torappu.Battle.Roguelike.Internal`


## Methods

- `Void ApplyAttributeInternal(AttributesData, Int32)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_DoPreProcess(ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike.Internal
public class CRandomTargetAttributeRandomMulti : BasicCharacterRelic
{
	private const String UPPER_BOUND_PREFIX; // 0x0
	private const String LOWER_BOUND_PREFIX; // 0x0
	private List`1 m_cachedCharacters; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_DoPreProcess; // 0x8
	private static DelegateBridge __Hotfix0_DoApplyAttribute; // 0x10
	private static DelegateBridge __Hotfix0_ApplyAttributeInternal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1d52a54 VA: 0x759436aa54
	public override Void OnInit() { }
	// RVA: 0x1d52e9c VA: 0x759436ae9c
	protected override Void DoPreProcess(ref RelicInOut inOut) { }
	// RVA: 0x1d52f78 VA: 0x759436af78
	protected virtual Void DoApplyAttribute(AttributesData attributesData) { }
	// RVA: 0x1d52ffc VA: 0x759436affc
	protected Void ApplyAttributeInternal(AttributesData attributes, Int32 stackLayer) { }
	// RVA: 0x1d5338c VA: 0x759436b38c
	public Void .ctor() { }
	// RVA: 0x1d53450 VA: 0x759436b450
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x1d53458 VA: 0x759436b458
	private Void <>xLuaBaseProxy_DoPreProcess(ref RelicInOut P0) { }
}
```