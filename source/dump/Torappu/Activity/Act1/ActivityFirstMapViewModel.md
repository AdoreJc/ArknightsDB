# ActivityFirstMapViewModel

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `String m_selectedZoneId`

- `String showZoneId`

- `DefaultZoneData m_cacheSelectedZoneData`

- `DefaultZoneData m_cacheShowZoneData`


## Properties

- `String selectedZoneId`

- `DefaultZoneData rightData`

- `DefaultZoneData leftData`

- `DefaultZoneData selectedZoneData`

- `DefaultZoneData showZoneData`


## Methods

- `String get_selectedZoneId()`

- `Void set_selectedZoneId(String)`

- `DefaultZoneData get_rightData()`

- `DefaultZoneData get_leftData()`

- `DefaultZoneData get_selectedZoneData()`

- `DefaultZoneData get_showZoneData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstMapViewModel : IHotfixable
{
	public List`1 zoneList; // 0x10
	private String m_selectedZoneId; // 0x18
	public String showZoneId; // 0x20
	private DefaultZoneData m_cacheSelectedZoneData; // 0x28
	private DefaultZoneData m_cacheShowZoneData; // 0x30
	private static DelegateBridge __Hotfix0_get_selectedZoneId; // 0x0
	private static DelegateBridge __Hotfix0_set_selectedZoneId; // 0x8
	private static DelegateBridge __Hotfix0_get_rightData; // 0x10
	private static DelegateBridge __Hotfix0_get_leftData; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedZoneData; // 0x20
	private static DelegateBridge __Hotfix0_get_showZoneData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String selectedZoneId { get; set; }
	public DefaultZoneData rightData { get; }
	public DefaultZoneData leftData { get; }
	public DefaultZoneData selectedZoneData { get; }
	public DefaultZoneData showZoneData { get; }

	// RVA: 0x348b460 VA: 0x7595aa3460
	public String get_selectedZoneId() { }
	// RVA: 0x348d930 VA: 0x7595aa5930
	public Void set_selectedZoneId(String value) { }
	// RVA: 0x348ddbc VA: 0x7595aa5dbc
	public DefaultZoneData get_rightData() { }
	// RVA: 0x348dba0 VA: 0x7595aa5ba0
	public DefaultZoneData get_leftData() { }
	// RVA: 0x3492230 VA: 0x7595aaa230
	public DefaultZoneData get_selectedZoneData() { }
	// RVA: 0x34916cc VA: 0x7595aa96cc
	public DefaultZoneData get_showZoneData() { }
	// RVA: 0x3492388 VA: 0x7595aaa388
	public Void .ctor() { }
}
```