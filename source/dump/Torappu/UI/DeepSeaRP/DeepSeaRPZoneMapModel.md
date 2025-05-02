# DeepSeaRPZoneMapModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `ZoneData m_zoneData`

- `Boolean m_isRetro`

- `ZoneData m_zoneAdditionData`

- `ZoneValidInfo m_zoneValidInfo`

- `ZoneStatus m_zoneStatus`


## Properties

- `ZoneStatus zoneStatus`

- `Int32 zoneIndex`

- `String zoneId`

- `String zoneName`

- `String lockedText`

- `Int64 startTime`


## Methods

- `ZoneStatus get_zoneStatus()`

- `Int32 get_zoneIndex()`

- `String get_zoneId()`

- `String get_zoneName()`

- `String get_lockedText()`

- `Int64 get_startTime()`

- `Void InitData(Boolean, ZoneData)`

- `Void _UpdateZoneStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPZoneMapModel : IHotfixable
{
	private ZoneData m_zoneData; // 0x10
	private Boolean m_isRetro; // 0x18
	private ZoneData m_zoneAdditionData; // 0x20
	private ZoneValidInfo m_zoneValidInfo; // 0x28
	private ZoneStatus m_zoneStatus; // 0x30
	private static DelegateBridge __Hotfix0_get_zoneStatus; // 0x0
	private static DelegateBridge __Hotfix0_get_zoneIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x10
	private static DelegateBridge __Hotfix0_get_zoneName; // 0x18
	private static DelegateBridge __Hotfix0_get_lockedText; // 0x20
	private static DelegateBridge __Hotfix0_get_startTime; // 0x28
	private static DelegateBridge __Hotfix0_InitData; // 0x30
	private static DelegateBridge __Hotfix0__UpdateZoneStatus; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public ZoneStatus zoneStatus { get; }
	public Int32 zoneIndex { get; }
	public String zoneId { get; }
	public String zoneName { get; }
	public String lockedText { get; }
	public Int64 startTime { get; }

	// RVA: 0x29d1194 VA: 0x7594fe9194
	public ZoneStatus get_zoneStatus() { }
	// RVA: 0x29d33b8 VA: 0x7594feb3b8
	public Int32 get_zoneIndex() { }
	// RVA: 0x29cca64 VA: 0x7594fe4a64
	public String get_zoneId() { }
	// RVA: 0x29ccb60 VA: 0x7594fe4b60
	public String get_zoneName() { }
	// RVA: 0x29d35dc VA: 0x7594feb5dc
	public String get_lockedText() { }
	// RVA: 0x29d3670 VA: 0x7594feb670
	public Int64 get_startTime() { }
	// RVA: 0x29d2924 VA: 0x7594fea924
	public Void InitData(Boolean isRetro, ZoneData act17sideZoneData) { }
	// RVA: 0x29d3458 VA: 0x7594feb458
	private Void _UpdateZoneStatus() { }
	// RVA: 0x29d28b4 VA: 0x7594fea8b4
	public Void .ctor() { }
}
```