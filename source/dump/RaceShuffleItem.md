# RaceShuffleItem

**Namespace:** ` `


## Fields

- `Boolean isOther`

- `EnemyHandbookRaceData data`


## Properties

- `String raceName`


## Methods

- `String get_raceName()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RaceShuffleItem : ShuffleItem
{
	public Boolean isOther; // 0x18
	public EnemyHandbookRaceData data; // 0x20
	private static DelegateBridge __Hotfix0_get_raceName; // 0x0
	private static DelegateBridge __Hotfix0_CheckViewModelMatch; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public String raceName { get; }

	// RVA: 0x293970c VA: 0x7594f5170c
	public String get_raceName() { }
	// RVA: 0x29397b8 VA: 0x7594f517b8
	public override Boolean CheckViewModelMatch(EnemyHandBookEverViewModel viewModel) { }
	// RVA: 0x2938b04 VA: 0x7594f50b04
	public Void .ctor() { }
}
```