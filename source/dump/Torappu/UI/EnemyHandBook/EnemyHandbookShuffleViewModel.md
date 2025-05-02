# EnemyHandbookShuffleViewModel

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `Int32 motionTypeSelectedCount`

- `Int32 attackTypeSelectedCount`

- `Int32 damageTypeSelectedCount`

- `Int32 raceSelectedCount`

- `BossShuffleItem bossShuffleItems`

- `Boolean isIncrease`


## Methods

- `ShufflePatch CreateShufflePatch()`

- `Boolean CheckShuffleInfo(EnemyHandBookEverViewModel)`

- `Void CleanShuffleSelect()`

- `Void InitShuffleViewModel()`

- `Void _dealWithMotionMode()`

- `Void _dealWithAttackType()`

- `Void _dealWithDamageType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandbookShuffleViewModel : IHotfixable
{
	public List`1 motionTypeList; // 0x10
	public Int32 motionTypeSelectedCount; // 0x18
	public List`1 attackTypeList; // 0x20
	public Int32 attackTypeSelectedCount; // 0x28
	public List`1 damageTypeList; // 0x30
	public Int32 damageTypeSelectedCount; // 0x38
	public List`1 raceShuffleItems; // 0x40
	public Int32 raceSelectedCount; // 0x48
	public BossShuffleItem bossShuffleItems; // 0x50
	public Boolean isIncrease; // 0x58
	private static DelegateBridge __Hotfix0_CreateShufflePatch; // 0x0
	private static DelegateBridge __Hotfix0_CheckShuffleInfo; // 0x8
	private static DelegateBridge __Hotfix0_CleanShuffleSelect; // 0x10
	private static DelegateBridge __Hotfix0_InitShuffleViewModel; // 0x18
	private static DelegateBridge __Hotfix0__dealWithMotionMode; // 0x20
	private static DelegateBridge __Hotfix0__dealWithAttackType; // 0x28
	private static DelegateBridge __Hotfix0__dealWithDamageType; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2937a90 VA: 0x7594f4fa90
	public ShufflePatch CreateShufflePatch() { }
	// RVA: 0x2937f0c VA: 0x7594f4ff0c
	public Boolean CheckShuffleInfo(EnemyHandBookEverViewModel everViewModel) { }
	// RVA: 0x29381fc VA: 0x7594f501fc
	public Void CleanShuffleSelect() { }
	// RVA: 0x29386b8 VA: 0x7594f506b8
	public Void InitShuffleViewModel() { }
	// RVA: 0x2938b70 VA: 0x7594f50b70
	private Void _dealWithMotionMode() { }
	// RVA: 0x2938d1c VA: 0x7594f50d1c
	private Void _dealWithAttackType() { }
	// RVA: 0x2938ec8 VA: 0x7594f50ec8
	private Void _dealWithDamageType() { }
	// RVA: 0x29391a0 VA: 0x7594f511a0
	public Void .ctor() { }
}
```