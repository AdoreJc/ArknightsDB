# DIYFilterModel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYFilterType m_filterType`

- `FurnitureSubType m_selectedSubType`

- `String m_displayName`

- `Boolean m_isFixed`

- `Boolean <hasTrackpoint>k__BackingField`


## Properties

- `Boolean hasTrackpoint`

- `DIYFilterType filterType`

- `String displayName`

- `Boolean isFixed`

- `FurnitureSubType selectedSubType`


## Methods

- `Boolean get_hasTrackpoint()`

- `Void set_hasTrackpoint(Boolean)`

- `DIYFilterType get_filterType()`

- `Void set_filterType(DIYFilterType)`

- `String get_displayName()`

- `Void set_displayName(String)`

- `Void set_subTypes(ListDict`2)`

- `Boolean get_isFixed()`

- `Void set_isFixed(Boolean)`

- `FurnitureSubType get_selectedSubType()`

- `Void set_selectedSubType(FurnitureSubType)`

- `Void ClearTrackpointStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFilterModel : IHotfixable
{
	private DIYFilterType m_filterType; // 0x10
	private FurnitureSubType m_selectedSubType; // 0x14
	private String m_displayName; // 0x18
	private Boolean m_isFixed; // 0x20
	private ListDict`2 m_subTypes; // 0x28
	private Boolean <hasTrackpoint>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_hasTrackpoint; // 0x0
	private static DelegateBridge __Hotfix0_set_hasTrackpoint; // 0x8
	private static DelegateBridge __Hotfix0_get_filterType; // 0x10
	private static DelegateBridge __Hotfix0_set_filterType; // 0x18
	private static DelegateBridge __Hotfix0_get_displayName; // 0x20
	private static DelegateBridge __Hotfix0_set_displayName; // 0x28
	private static DelegateBridge __Hotfix0_get_subTypes; // 0x30
	private static DelegateBridge __Hotfix0_set_subTypes; // 0x38
	private static DelegateBridge __Hotfix0_get_isFixed; // 0x40
	private static DelegateBridge __Hotfix0_set_isFixed; // 0x48
	private static DelegateBridge __Hotfix0_get_selectedSubType; // 0x50
	private static DelegateBridge __Hotfix0_set_selectedSubType; // 0x58
	private static DelegateBridge __Hotfix0_ClearTrackpointStatus; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Boolean hasTrackpoint { get; set; }
	public DIYFilterType filterType { get; set; }
	public String displayName { get; set; }
	public ListDict`2 subTypes { get; set; }
	public Boolean isFixed { get; set; }
	public FurnitureSubType selectedSubType { get; set; }

	// RVA: 0x383e2c4 VA: 0x7595e562c4
	public Boolean get_hasTrackpoint() { }
	// RVA: 0x383de44 VA: 0x7595e55e44
	public Void set_hasTrackpoint(Boolean value) { }
	// RVA: 0x383d060 VA: 0x7595e55060
	public DIYFilterType get_filterType() { }
	// RVA: 0x383cfe4 VA: 0x7595e54fe4
	public Void set_filterType(DIYFilterType value) { }
	// RVA: 0x383e32c VA: 0x7595e5632c
	public String get_displayName() { }
	// RVA: 0x383d57c VA: 0x7595e5557c
	public Void set_displayName(String value) { }
	// RVA: 0x383d600 VA: 0x7595e55600
	public ListDict`2 get_subTypes() { }
	// RVA: 0x383e394 VA: 0x7595e56394
	public Void set_subTypes(ListDict`2 value) { }
	// RVA: 0x383e418 VA: 0x7595e56418
	public Boolean get_isFixed() { }
	// RVA: 0x383cf64 VA: 0x7595e54f64
	public Void set_isFixed(Boolean value) { }
	// RVA: 0x383cd54 VA: 0x7595e54d54
	public FurnitureSubType get_selectedSubType() { }
	// RVA: 0x383d9f8 VA: 0x7595e559f8
	public Void set_selectedSubType(FurnitureSubType value) { }
	// RVA: 0x383d864 VA: 0x7595e55864
	public Void ClearTrackpointStatus() { }
	// RVA: 0x383cea0 VA: 0x7595e54ea0
	public Void .ctor() { }
}
```