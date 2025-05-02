# TOrderSlotGroupViewModel

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `String m_roomIdCache`

- `TradingInfoViewStruct info`

- `Int32 nonEmptySlotCount`

- `Boolean hasGainingSlot`


## Methods

- `Void LoadData(TRoomViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class TOrderSlotGroupViewModel : IHotfixable
{
	private String m_roomIdCache; // 0x10
	private ListDict`2 m_sortList; // 0x18
	public TradingInfoViewStruct info; // 0x20
	public Int32 nonEmptySlotCount; // 0xa0
	public Boolean hasGainingSlot; // 0xa4
	public List`1 slots; // 0xa8
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3d81eac VA: 0x7596399eac
	public Void LoadData(TRoomViewModel roomModel) { }
	// RVA: 0x3d82c3c VA: 0x759639ac3c
	public Void .ctor() { }
}
```