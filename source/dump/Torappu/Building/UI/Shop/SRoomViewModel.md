# SRoomViewModel

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `BasicRoomInfoModel basicInfo`

- `ShopInfoViewModel shopInfo`


## Methods

- `BasicRoomInfoModel GetRoomInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class SRoomViewModel : IBasicRoomModel, IHotfixable
{
	public BasicRoomInfoModel basicInfo; // 0x10
	public ShopInfoViewModel shopInfo; // 0x40
	private static DelegateBridge __Hotfix0_GetRoomInfo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3dbaaec VA: 0x75963d2aec
	public BasicRoomInfoModel GetRoomInfo() { }
	// RVA: 0x3db9a30 VA: 0x75963d1a30
	public Void .ctor() { }
}
```