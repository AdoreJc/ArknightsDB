# RhineBattlePerformanceItemModel

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `String itemId`

- `Int32 sortId`

- `String itemName`

- `String itemDesc`

- `String itemIconId`

- `Boolean isNew`

- `Boolean isUnlock`


## Methods

- `Void LoadData(BattlePerformanceData, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class RhineBattlePerformanceItemModel : IHotfixable
{
	public String itemId; // 0x10
	public Int32 sortId; // 0x18
	public String itemName; // 0x20
	public String itemDesc; // 0x28
	public String itemIconId; // 0x30
	public Boolean isNew; // 0x38
	public Boolean isUnlock; // 0x39
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3289cc0 VA: 0x75958a1cc0
	public Void LoadData(BattlePerformanceData itemData, String groupId) { }
	// RVA: 0x3289c50 VA: 0x75958a1c50
	public Void .ctor() { }
}
```