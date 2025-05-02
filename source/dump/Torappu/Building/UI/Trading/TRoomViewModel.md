# TRoomViewModel

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `BasicRoomInfoModel basicInfo`

- `TradingInfoViewStruct info`


## Methods

- `BasicRoomInfoModel GetRoomInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class TRoomViewModel : IBasicRoomModel, IHotfixable
{
	public BasicRoomInfoModel basicInfo; // 0x10
	public TradingInfoViewStruct info; // 0x40
	private static DelegateBridge __Hotfix0_GetRoomInfo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3d82968 VA: 0x759639a968
	public BasicRoomInfoModel GetRoomInfo() { }
	// RVA: 0x3d81c90 VA: 0x7596399c90
	public Void .ctor() { }
}
```