# SandboxV2DungeonEnemyRushViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String enemyRushGroupKey`

- `Int32 totEnemyCount`

- `Int32 currEnemyCount`

- `SandboxV2EnemyRushType type`

- `Int32 typeSortId`

- `Int32 remainDays`

- `Int32 enemyState`


## Properties

- `Boolean completed`

- `Single enemyRushRatio`


## Methods

- `Boolean get_completed()`

- `Single get_enemyRushRatio()`

- `Void UpdateData(UpdateParam)`

- `Int32 <>xLuaBaseProxy_CompareDungeonFloat(SandboxV2DungeonFloatViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonEnemyRushViewModel : SandboxV2DungeonFloatViewModel
{
	public String enemyRushGroupKey; // 0x60
	public ListDict`2 enemyRushDrop; // 0x68
	public Int32 totEnemyCount; // 0x70
	public Int32 currEnemyCount; // 0x74
	public List`1 enemies; // 0x78
	public List`1 bosses; // 0x80
	public SandboxV2EnemyRushType type; // 0x88
	public Int32 typeSortId; // 0x8c
	public Int32 remainDays; // 0x90
	public Int32 enemyState; // 0x94
	private static DelegateBridge __Hotfix0_get_completed; // 0x0
	private static DelegateBridge __Hotfix0_get_enemyRushRatio; // 0x8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x10
	private static DelegateBridge __Hotfix0_CompareDungeonFloat; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean completed { get; }
	public Single enemyRushRatio { get; }

	// RVA: 0x25bf484 VA: 0x7594bd7484
	public Boolean get_completed() { }
	// RVA: 0x25bf504 VA: 0x7594bd7504
	public Single get_enemyRushRatio() { }
	// RVA: 0x25bf588 VA: 0x7594bd7588
	public Void UpdateData(UpdateParam updateParam) { }
	// RVA: 0x25bfc74 VA: 0x7594bd7c74
	public override Int32 CompareDungeonFloat(SandboxV2DungeonFloatViewModel other) { }
	// RVA: 0x25bfd94 VA: 0x7594bd7d94
	public Void .ctor() { }
	// RVA: 0x25bfef4 VA: 0x7594bd7ef4
	private Int32 <>xLuaBaseProxy_CompareDungeonFloat(SandboxV2DungeonFloatViewModel P0) { }
}
```