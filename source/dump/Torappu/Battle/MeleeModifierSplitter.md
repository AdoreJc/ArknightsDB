# MeleeModifierSplitter

**Namespace:** `Torappu.Battle`


## Fields

- `ApplyModifier m_sharedSplittedNode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MeleeModifierSplitter : ModifierSplitter
{
	private ApplyModifier m_sharedSplittedNode; // 0x28


	// RVA: 0x40a0444 VA: 0x75966b8444
	public Void .ctor(Options options) { }
	// RVA: 0x40a04c4 VA: 0x75966b84c4
	public override Void Reset(IList`1 actions, ApplyDamage damageNode) { }
	// RVA: 0x40a0504 VA: 0x75966b8504
	protected override Void OnBeforeApply(KeyValuePair`2 pair) { }
	// RVA: 0x40a0508 VA: 0x75966b8508
	protected override Void OnAfterApply() { }
	// RVA: 0x40a050c VA: 0x75966b850c
	protected override KeyValuePair`2 CreateModifierPair(ref Modifier modifier) { }
}
```