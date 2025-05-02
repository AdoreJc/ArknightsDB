# CrisisV2RunePackViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String m_mapId`

- `String m_bagId`

- `Int32 m_bagSortId`


## Properties

- `String bagId`


## Methods

- `String get_bagId()`

- `Void LoadData(String, String, Int32)`

- `Int32 CompareTo(CrisisV2RunePackViewModel)`

- `String <>xLuaBaseProxy_GetGlobalId()`

- `ViewType <>xLuaBaseProxy_GetDetailViewType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2RunePackViewModel : CrisisV2RuneBaseViewModel, IComparable`1
{
	public List`1 runeItemViewModels; // 0x18
	private String m_mapId; // 0x20
	private String m_bagId; // 0x28
	private Int32 m_bagSortId; // 0x30
	private static DelegateBridge __Hotfix0_get_bagId; // 0x0
	private static DelegateBridge __Hotfix0_GetGlobalId; // 0x8
	private static DelegateBridge __Hotfix0_GetDetailViewType; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_CompareTo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String bagId { get; }

	// RVA: 0x2bf6098 VA: 0x759520e098
	public String get_bagId() { }
	// RVA: 0x2bf6100 VA: 0x759520e100
	public override String GetGlobalId() { }
	// RVA: 0x2bf6184 VA: 0x759520e184
	public override ViewType GetDetailViewType() { }
	// RVA: 0x2bf61ec VA: 0x759520e1ec
	public Void LoadData(String mapId, String bagId, Int32 bagSortId) { }
	// RVA: 0x2bf62a4 VA: 0x759520e2a4
	public Int32 CompareTo(CrisisV2RunePackViewModel other) { }
	// RVA: 0x2bf6354 VA: 0x759520e354
	public Void .ctor() { }
	// RVA: 0x2bf6418 VA: 0x759520e418
	private String <>xLuaBaseProxy_GetGlobalId() { }
	// RVA: 0x2bf6420 VA: 0x759520e420
	private ViewType <>xLuaBaseProxy_GetDetailViewType() { }
}
```