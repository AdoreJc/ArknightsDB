# RangedModifierSplitter

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 damageNodeIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RangedModifierSplitter : ModifierSplitter
{
	private Int32 damageNodeIndex; // 0x28
	private IList`1 m_actions; // 0x30


	// RVA: 0x40a05b8 VA: 0x75966b85b8
	public Void .ctor(Options options) { }
	// RVA: 0x40a05c0 VA: 0x75966b85c0
	public override Void Reset(IList`1 actions, ApplyDamage damageNode) { }
	// RVA: 0x40a06a4 VA: 0x75966b86a4
	protected override Void OnBeforeApply(KeyValuePair`2 pair) { }
	// RVA: 0x40a0768 VA: 0x75966b8768
	protected override Void OnAfterApply() { }
	// RVA: 0x40a081c VA: 0x75966b881c
	protected override KeyValuePair`2 CreateModifierPair(ref Modifier modifier) { }
}
```