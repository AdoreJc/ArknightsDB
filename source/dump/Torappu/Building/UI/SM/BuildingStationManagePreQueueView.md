# BuildingStationManagePreQueueView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `CharAdapterForPreQueue m_charAdapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(StationManageEditRoomQueueStructModel, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingStationManagePreQueueView : BuildingStationManageQueueBaseView, IHotfixable
{
	private CharAdapterForPreQueue m_charAdapter; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0_get_charAdapter; // 0x0
	private static DelegateBridge __Hotfix0_InitAdapter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override CharAdapter charAdapter { get; }

	// RVA: 0x3db1e9c VA: 0x75963c9e9c
	protected override CharAdapter get_charAdapter() { }
	// RVA: 0x3db1f64 VA: 0x75963c9f64
	protected override Void InitAdapter() { }
	// RVA: 0x3db2094 VA: 0x75963ca094
	private Void _InitIfNot() { }
	// RVA: 0x3db21a4 VA: 0x75963ca1a4
	public Void Render(StationManageEditRoomQueueStructModel queueStructModel, Int32 preQueueIndex) { }
	// RVA: 0x3db22fc VA: 0x75963ca2fc
	public Void .ctor() { }
}
```