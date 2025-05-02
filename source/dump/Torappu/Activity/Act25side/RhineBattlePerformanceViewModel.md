# RhineBattlePerformanceViewModel

**Namespace:** `Torappu.Activity.Act25side`


## Methods

- `Void LoadData(Boolean, String)`

- `RhineBattlePerformanceItemListModel GetItemModelByType(Act25sideTechType)`

- `RhineBattlePerformanceItemListModel _GeneDefaultListModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class RhineBattlePerformanceViewModel : IHotfixable
{
	public Dictionary`2 battlePerformanceItems; // 0x10
	public List`1 unlockItemIds; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_GetItemModelByType; // 0x8
	private static DelegateBridge __Hotfix0__GeneDefaultListModel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x32895ec VA: 0x75958a15ec
	public Void LoadData(Boolean isRetro, String groupId) { }
	// RVA: 0x328a100 VA: 0x75958a2100
	public RhineBattlePerformanceItemListModel GetItemModelByType(Act25sideTechType type) { }
	// RVA: 0x3289ed8 VA: 0x75958a1ed8
	private RhineBattlePerformanceItemListModel _GeneDefaultListModel() { }
	// RVA: 0x328a19c VA: 0x75958a219c
	public Void .ctor() { }
}
```