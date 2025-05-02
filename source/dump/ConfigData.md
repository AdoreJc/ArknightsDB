# ConfigData

**Namespace:** ` `


## Fields

- `String numberUnitFormat`

- `Int32 unitStepSize`

- `Int32 battleResultCharWordLineLength`

- `BattleResultCharWordSplitMode splitMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ConfigData : IHotfixable
{
	public String numberUnitFormat; // 0x10
	public String[] numberUnits; // 0x18
	public Int32 unitStepSize; // 0x20
	public Int32 battleResultCharWordLineLength; // 0x24
	public BattleResultCharWordSplitMode splitMode; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x35ba56c VA: 0x7595bd256c
	public Void .ctor(LocalizationPreferenceConfig config) { }
}
```