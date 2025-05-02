# PeriodModifySharedDataBbTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Single _period`

- `String _valueKey`

- `String _addKey`

- `String _maxKey`

- `String _initKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class PeriodModifySharedDataBbTalent : CardHoldTalent
{
	private Single _period; // 0x50
	private String _valueKey; // 0x58
	private String _addKey; // 0x60
	private String _maxKey; // 0x68
	private String _initKey; // 0x70
	private static DelegateBridge __Hotfix0_CreateCardEffectPlugin; // 0x0
	private static DelegateBridge __Hotfix0_CreateHoldDataModifier; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b80468 VA: 0x7594198468
	public override CardEffectPlugin CreateCardEffectPlugin(Character character, CardHoldDataModifier modifier) { }
	// RVA: 0x1b80748 VA: 0x7594198748
	public override CardHoldDataModifier CreateHoldDataModifier(Character character) { }
	// RVA: 0x1b80ad4 VA: 0x7594198ad4
	public Void .ctor() { }
}
```