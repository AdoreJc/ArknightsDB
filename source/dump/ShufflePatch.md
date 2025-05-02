# ShufflePatch

**Namespace:** ` `


## Fields

- `Int32 motionTypeSelectedCount`

- `Int32 attackTypeSelectedCount`

- `Int32 damageTypeSelectedCount`

- `Int32 raceSelectedCount`

- `EnemyLevelMask levelMask`


## Methods

- `Boolean SelectedCountEqual(ShufflePatch)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ShufflePatch : IHotfixable
{
	public Int32 motionTypeSelectedCount; // 0x10
	public Int32 attackTypeSelectedCount; // 0x14
	public Int32 damageTypeSelectedCount; // 0x18
	public Int32 raceSelectedCount; // 0x1c
	public EnemyLevelMask levelMask; // 0x20
	private static DelegateBridge __Hotfix0_SelectedCountEqual; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2937b54 VA: 0x7594f4fb54
	public Boolean SelectedCountEqual(ShufflePatch patch) { }
	// RVA: 0x2937e94 VA: 0x7594f4fe94
	public Void .ctor() { }
}
```