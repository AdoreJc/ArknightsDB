# RushEnemy

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `SandboxV2EnemyRushType type`

- `String uid`

- `String groupId`

- `Int32 groupIndex`

- `Int32 count`

- `Int32 totalCount`

- `Boolean isRareAnimal`

- `RareAnimalExtraInfo extra`

- `String enemyId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class RushEnemy : IHotfixable
{
	public SandboxV2EnemyRushType type; // 0x10
	public String uid; // 0x18
	public String groupId; // 0x20
	public Int32 groupIndex; // 0x28
	public Int32 count; // 0x2c
	public Int32 totalCount; // 0x30
	public Boolean isRareAnimal; // 0x34
	public RareAnimalExtraInfo extra; // 0x38
	public String enemyId; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x1df8818 VA: 0x7594410818
	public Void .ctor() { }
}
```