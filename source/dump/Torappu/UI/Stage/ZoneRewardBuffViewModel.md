# ZoneRewardBuffViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String itemId`

- `String itemName`

- `String itemNameEng`

- `Int64 startTs`

- `Int64 endTs`

- `String zoneRange`

- `String itemDesc`

- `String itemHowUse`

- `String itemHowGain`

- `Boolean isValid`

- `Int32 useTime`

- `Int32 itemNum`

- `String itemIconId`

- `ItemType itemType`

- `Int32 m_dayCanUseTotalTime`


## Methods

- `Void LoadData(String)`

- `Void RefreshData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRewardBuffViewModel : IHotfixable
{
	public String itemId; // 0x10
	public String itemName; // 0x18
	public String itemNameEng; // 0x20
	public Int64 startTs; // 0x28
	public Int64 endTs; // 0x30
	public String zoneRange; // 0x38
	public String itemDesc; // 0x40
	public String itemHowUse; // 0x48
	public String itemHowGain; // 0x50
	public Boolean isValid; // 0x58
	public Int32 useTime; // 0x5c
	public Int32 itemNum; // 0x60
	public String itemIconId; // 0x68
	public ItemType itemType; // 0x70
	private Int32 m_dayCanUseTotalTime; // 0x74
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2fc77e4 VA: 0x75955df7e4
	public Void LoadData(String zoneId) { }
	// RVA: 0x2fc7b78 VA: 0x75955dfb78
	public Void RefreshData() { }
	// RVA: 0x2fc7cb4 VA: 0x75955dfcb4
	public Void .ctor() { }
}
```