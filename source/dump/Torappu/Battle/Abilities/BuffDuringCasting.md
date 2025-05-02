# BuffDuringCasting

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void GatherEffects(List`1)`

- `Void GatherBuffs(List`1)`

- `Void _ClearBuffs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BuffDuringCasting : Behaviour, IEffectSource, IBuffSource
{
	private BuffData[] _buffs; // 0x20
	private List`1 m_buffUid; // 0x28


	// RVA: 0x1ebd2e8 VA: 0x75944d52e8
	public override Void OnCastStart() { }
	// RVA: 0x1ebd4c0 VA: 0x75944d54c0
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ebd4dc VA: 0x75944d54dc
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ebd4f0 VA: 0x75944d54f0
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ebd408 VA: 0x75944d5408
	private Void _ClearBuffs() { }
	// RVA: 0x1ebd548 VA: 0x75944d5548
	public Void .ctor() { }
}
```