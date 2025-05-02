# UniEquipArchiveFilterHolder

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `UniEquipArchiveFilterView _filterView`

- `UniEquipArchiveFilterProperty m_prop`


## Methods

- `Void ApplyTrackNum(Int32)`

- `Void _ApplyData()`

- `Void _OnShowTrackClick(Boolean)`

- `Void _OnUnlockTabClick(UniEquipArchiveFilterEquipState)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveFilterHolder : UICharacterFilterHolder
{
	private UniEquipArchiveFilterView _filterView; // 0x28
	private UniEquipArchiveFilterProperty m_prop; // 0x30
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_ApplyTrackNum; // 0x8
	private static DelegateBridge __Hotfix0__ApplyData; // 0x10
	private static DelegateBridge __Hotfix0__OnShowTrackClick; // 0x18
	private static DelegateBridge __Hotfix0__OnUnlockTabClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x22e45bc VA: 0x75948fc5bc
	protected override Void OnCreate() { }
	// RVA: 0x22e48e8 VA: 0x75948fc8e8
	public Void ApplyTrackNum(Int32 trackNum) { }
	// RVA: 0x22e47dc VA: 0x75948fc7dc
	private Void _ApplyData() { }
	// RVA: 0x22e49d4 VA: 0x75948fc9d4
	private Void _OnShowTrackClick(Boolean showTrack) { }
	// RVA: 0x22e4b3c VA: 0x75948fcb3c
	private Void _OnUnlockTabClick(UniEquipArchiveFilterEquipState filterState) { }
	// RVA: 0x22e4c28 VA: 0x75948fcc28
	public Void .ctor() { }
}
```