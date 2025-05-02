# EnemyDuelTopBarViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String roomName`

- `Boolean isEmoticonDisabled`

- `Int32 loadSeqNum`

- `String defaultEmoticonGroupId`

- `String defaultEmoticonPicId`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelTopBarViewModel : IHotfixable
{
	public List`1 pingConds; // 0x10
	public String roomName; // 0x18
	public Boolean isEmoticonDisabled; // 0x20
	public Int32 loadSeqNum; // 0x24
	public String defaultEmoticonGroupId; // 0x28
	public String defaultEmoticonPicId; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2982380 VA: 0x7594f9a380
	public Void LoadData() { }
	// RVA: 0x29824c0 VA: 0x7594f9a4c0
	public Void .ctor() { }
}
```