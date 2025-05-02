# EndAnimEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void _PlayEffectsInNextFrame()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class EndAnimEffectEmitter : AbstractEffectEmitter
{
	private String[] _effectKeys; // 0x20
	private static DelegateBridge __Hotfix0_OnEvent; // 0x0
	private static DelegateBridge __Hotfix0__PlayEffectsInNextFrame; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1ec3300 VA: 0x75944db300
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ec340c VA: 0x75944db40c
	private Void _PlayEffectsInNextFrame() { }
	// RVA: 0x1ec3638 VA: 0x75944db638
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ec36d8 VA: 0x75944db6d8
	public Void .ctor() { }
	// RVA: 0x1ec3744 VA: 0x75944db744
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```