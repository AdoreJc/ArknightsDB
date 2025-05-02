# DIYFilterGroupModel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYFilterType selectedFilterType`

- `Boolean isHide`

- `Boolean isReset`


## Properties

- `FurnitureSubType selectedSubType`


## Methods

- `FurnitureSubType get_selectedSubType()`

- `Void _LoadALLFilter()`

- `Void _LoadFilters()`

- `Void _ClearTrackpointStatus()`

- `Void LoadData()`

- `Boolean SetSelectFilterType(DIYFilterType)`

- `Boolean SetSelectFilterSubType(FurnitureSubType)`

- `Void UpdateTrackpointStatus(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFilterGroupModel : IHotfixable
{
	public DIYFilterType selectedFilterType; // 0x10
	public ListDict`2 recentFurnitures; // 0x18
	public Boolean isHide; // 0x20
	public Boolean isReset; // 0x21
	private ListDict`2 m_filterModels; // 0x28
	private static DelegateBridge __Hotfix0_get_filterModels; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedSubType; // 0x8
	private static DelegateBridge __Hotfix0__LoadALLFilter; // 0x10
	private static DelegateBridge __Hotfix0__LoadFilters; // 0x18
	private static DelegateBridge __Hotfix0__ClearTrackpointStatus; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_SetSelectFilterType; // 0x30
	private static DelegateBridge __Hotfix0_SetSelectFilterSubType; // 0x38
	private static DelegateBridge __Hotfix0_UpdateTrackpointStatus; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public ListDict`2 filterModels { get; }
	public FurnitureSubType selectedSubType { get; }

	// RVA: 0x383ccec VA: 0x7595e54cec
	public ListDict`2 get_filterModels() { }
	// RVA: 0x3834560 VA: 0x7595e4c560
	public FurnitureSubType get_selectedSubType() { }
	// RVA: 0x383cdbc VA: 0x7595e54dbc
	private Void _LoadALLFilter() { }
	// RVA: 0x383d0c8 VA: 0x7595e550c8
	private Void _LoadFilters() { }
	// RVA: 0x383d6d8 VA: 0x7595e556d8
	private Void _ClearTrackpointStatus() { }
	// RVA: 0x383263c VA: 0x7595e4a63c
	public Void LoadData() { }
	// RVA: 0x3835714 VA: 0x7595e4d714
	public Boolean SetSelectFilterType(DIYFilterType filterType) { }
	// RVA: 0x3835ca8 VA: 0x7595e4dca8
	public Boolean SetSelectFilterSubType(FurnitureSubType subType) { }
	// RVA: 0x3834a3c VA: 0x7595e4ca3c
	public Void UpdateTrackpointStatus(Boolean useRecent) { }
	// RVA: 0x383da7c VA: 0x7595e55a7c
	public Void .ctor() { }
}
```