# SandboxV2DungeonEnemyRushGroupViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 enemyRushStackCount`

- `Single enemyRushRatio`

- `SandboxV2DungeonProgressViewModel enemyRushProgressModel`


## Methods

- `Boolean IsEmpty()`

- `Void Clear()`

- `Void AddEnemyRush(SandboxV2DungeonEnemyRushViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonEnemyRushGroupViewModel : IHotfixable
{
	public List`1 enemyRushList; // 0x10
	public Int32 enemyRushStackCount; // 0x18
	public Single enemyRushRatio; // 0x1c
	public SandboxV2DungeonProgressViewModel enemyRushProgressModel; // 0x20
	public ListDict`2 enemyRushGroupDrop; // 0x30
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x0
	private static DelegateBridge __Hotfix0_Clear; // 0x8
	private static DelegateBridge __Hotfix0_AddEnemyRush; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25b7c00 VA: 0x7594bcfc00
	public Boolean IsEmpty() { }
	// RVA: 0x25bfef8 VA: 0x7594bd7ef8
	public Void Clear() { }
	// RVA: 0x25bffe8 VA: 0x7594bd7fe8
	public Void AddEnemyRush(SandboxV2DungeonEnemyRushViewModel enemyRush) { }
	// RVA: 0x25bb94c VA: 0x7594bd394c
	public Void .ctor() { }
}
```