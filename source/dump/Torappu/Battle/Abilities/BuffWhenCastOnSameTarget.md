# BuffWhenCastOnSameTarget

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void GatherBuffs(List`1)`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BuffWhenCastOnSameTarget : Behaviour, IEffectSource, IBuffSource
{
	private BuffData[] _buffsWhenCastOnSameTarget; // 0x20
	private BuffData[] _buffsWhenSwitchTarget; // 0x28
	private ObjectPtr`1 m_validCastTarget; // 0x30
	private ObjectPtr`1 m_lastCastTarget; // 0x40
	private static DelegateBridge __Hotfix0_OnEvent; // 0x0
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1ebf678 VA: 0x75944d7678
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ebf8dc VA: 0x75944d78dc
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ebf98c VA: 0x75944d798c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ebfa10 VA: 0x75944d7a10
	public Void .ctor() { }
	// RVA: 0x1ebfad8 VA: 0x75944d7ad8
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```