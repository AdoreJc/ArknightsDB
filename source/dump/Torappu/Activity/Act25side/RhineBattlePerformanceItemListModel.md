# RhineBattlePerformanceItemListModel

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `String displayName`

- `String displayDesc`

- `Boolean lowLevelUnlock`

- `Boolean lowLevelNew`

- `Boolean highLevelUnlock`

- `Boolean highLevelNew`


## Methods

- `Void InputItem(RhineBattlePerformanceItemModel)`

- `Void UpdateDisplayInfo()`

- `String GetLowLevelItemIconId()`

- `String GetHighLevelItemIconId()`

- `String _GetLevelItemIconByIndex(Int32)`

- `Void _SortBySortId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class RhineBattlePerformanceItemListModel : IHotfixable
{
	public const String LOCK_ITEM_ICON_ID; // 0x0
	public String displayName; // 0x10
	public String displayDesc; // 0x18
	public Boolean lowLevelUnlock; // 0x20
	public Boolean lowLevelNew; // 0x21
	public Boolean highLevelUnlock; // 0x22
	public Boolean highLevelNew; // 0x23
	private List`1 m_itemList; // 0x28
	private static DelegateBridge __Hotfix0_InputItem; // 0x0
	private static DelegateBridge __Hotfix0_UpdateDisplayInfo; // 0x8
	private static DelegateBridge __Hotfix0_GetLowLevelItemIconId; // 0x10
	private static DelegateBridge __Hotfix0_GetHighLevelItemIconId; // 0x18
	private static DelegateBridge __Hotfix0__GetLevelItemIconByIndex; // 0x20
	private static DelegateBridge __Hotfix0__SortBySortId; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3289ddc VA: 0x75958a1ddc
	public Void InputItem(RhineBattlePerformanceItemModel item) { }
	// RVA: 0x3289f6c VA: 0x75958a1f6c
	public Void UpdateDisplayInfo() { }
	// RVA: 0x328a3f4 VA: 0x75958a23f4
	public String GetLowLevelItemIconId() { }
	// RVA: 0x328a524 VA: 0x75958a2524
	public String GetHighLevelItemIconId() { }
	// RVA: 0x328a460 VA: 0x75958a2460
	private String _GetLevelItemIconByIndex(Int32 index) { }
	// RVA: 0x328a2b0 VA: 0x75958a22b0
	private Void _SortBySortId() { }
	// RVA: 0x3289b8c VA: 0x75958a1b8c
	public Void .ctor() { }
}
```