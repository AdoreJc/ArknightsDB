# CRandomTargetAttribute

**Namespace:** `Torappu.Battle.Roguelike.Internal`


## Methods

- `Void ApplyAttributeInternal(AttributesData, Int32)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_DoPreProcess(ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike.Internal
public class CRandomTargetAttribute : BasicCharacterRelic
{
	protected const String EFFECT_DYNAMIC_ABILITY; // 0x0
	protected const String DYNAMIC_ABILITY_KEY; // 0x0
	protected List`1 m_cachedCharacters; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_DoPreProcess; // 0x8
	private static DelegateBridge __Hotfix0_DoApplyAttribute; // 0x10
	private static DelegateBridge __Hotfix0_ApplyAttributeInternal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1d51228 VA: 0x7594369228
	public override Void OnInit() { }
	// RVA: 0x1d51670 VA: 0x7594369670
	protected override Void DoPreProcess(ref RelicInOut inOut) { }
	// RVA: 0x1d519d4 VA: 0x75943699d4
	protected virtual Void DoApplyAttribute(AttributesData attributesData) { }
	// RVA: 0x1d51a58 VA: 0x7594369a58
	protected Void ApplyAttributeInternal(AttributesData attributes, Int32 stackLayer) { }
	// RVA: 0x1d51db4 VA: 0x7594369db4
	public Void .ctor() { }
	// RVA: 0x1d51e78 VA: 0x7594369e78
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x1d51e80 VA: 0x7594369e80
	private Void <>xLuaBaseProxy_DoPreProcess(ref RelicInOut P0) { }
}
```