# FireworkPlateGroupModel

**Namespace:** `Torappu.UI.Firework`


## Fields

- `FireworkPlateModel plateModel`

- `Int32 maxFilledPlatePieceCount`

- `PlateSlotData selectedPlatePiece`

- `PlateContentModel selectedPlateContentModel`

- `PlateSlotData lastFilledPlatePiece`

- `PlateContentModel lastFilledPlateContentModel`

- `Boolean hasLockedPlate`

- `Boolean showNewMark`

- `String previewingPlateGroupId`

- `Boolean isClearAllExpand`

- `Int32 loadSequenceNum`

- `Int32 addPieceSeqNum`

- `Int32 removePieceSeqNum`

- `Int32 hintUpdateSeqNum`


## Methods

- `Void LoadData(LoadParam)`

- `Void UpdateHintList(List`1)`

- `Void _UpdateHintList(List`1)`

- `Int32 GetGroupHintCount(String)`

- `Boolean IsPieceHinted(PlateSlotData)`

- `Void SetSelection(PlateSlotData)`

- `Void ClearSelection()`

- `Void SetPreviewingPlateGroup(String)`

- `Void ClearPreviewingPlateGroup()`

- `Void FillPlatePiece(PlateSlotData)`

- `Void ClearFilledPlatePiece()`

- `Int32 GetPlateSlotFilledIndex(PlateSlotData)`

- `Int32 GetFirstEmptyPlateSlotIndex()`

- `Int32 GetPlateGroupFilledCount(String)`

- `Void GenNotNullFilledPlateList(List`1)`

- `Int32 GetFilledCount()`

- `Boolean IsLastPlateValid()`

- `Boolean IsAllEquipPlateValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateGroupModel : IHotfixable
{
	private List`1 m_hintPlatePieceList; // 0x10
	public FireworkPlateModel plateModel; // 0x18
	public ListDict`2 platePieceList; // 0x20
	public PlateSlotData[] filledPlatePieceList; // 0x28
	public Int32 maxFilledPlatePieceCount; // 0x30
	public PlateSlotData selectedPlatePiece; // 0x38
	public PlateContentModel selectedPlateContentModel; // 0x40
	public PlateSlotData lastFilledPlatePiece; // 0x48
	public PlateContentModel lastFilledPlateContentModel; // 0x50
	public Boolean hasLockedPlate; // 0x58
	public Boolean showNewMark; // 0x59
	public String previewingPlateGroupId; // 0x60
	public Boolean isClearAllExpand; // 0x68
	public Int32 loadSequenceNum; // 0x6c
	public Int32 addPieceSeqNum; // 0x70
	public Int32 removePieceSeqNum; // 0x74
	public Int32 hintUpdateSeqNum; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateHintList; // 0x8
	private static DelegateBridge __Hotfix0__UpdateHintList; // 0x10
	private static DelegateBridge __Hotfix0_GetGroupHintCount; // 0x18
	private static DelegateBridge __Hotfix0_IsPieceHinted; // 0x20
	private static DelegateBridge __Hotfix0_SetSelection; // 0x28
	private static DelegateBridge __Hotfix0_ClearSelection; // 0x30
	private static DelegateBridge __Hotfix0_SetPreviewingPlateGroup; // 0x38
	private static DelegateBridge __Hotfix0_ClearPreviewingPlateGroup; // 0x40
	private static DelegateBridge __Hotfix0_FillPlatePiece; // 0x48
	private static DelegateBridge __Hotfix0_ClearFilledPlatePiece; // 0x50
	private static DelegateBridge __Hotfix0_GetPlateSlotFilledIndex; // 0x58
	private static DelegateBridge __Hotfix0_GetFirstEmptyPlateSlotIndex; // 0x60
	private static DelegateBridge __Hotfix0_GetPlateGroupFilledCount; // 0x68
	private static DelegateBridge __Hotfix0_GenNotNullFilledPlateList; // 0x70
	private static DelegateBridge __Hotfix0_GetFilledCount; // 0x78
	private static DelegateBridge __Hotfix0_IsLastPlateValid; // 0x80
	private static DelegateBridge __Hotfix0_IsAllEquipPlateValid; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x28ed92c VA: 0x7594f0592c
	public Void LoadData(LoadParam loadParam) { }
	// RVA: 0x28ee620 VA: 0x7594f06620
	public Void UpdateHintList(List`1 hintPieceList) { }
	// RVA: 0x28ee58c VA: 0x7594f0658c
	private Void _UpdateHintList(List`1 hintPieceList) { }
	// RVA: 0x28ee6a0 VA: 0x7594f066a0
	public Int32 GetGroupHintCount(String groupId) { }
	// RVA: 0x28ee7c0 VA: 0x7594f067c0
	public Boolean IsPieceHinted(PlateSlotData platePiece) { }
	// RVA: 0x28eb168 VA: 0x7594f03168
	public Void SetSelection(PlateSlotData platePiece) { }
	// RVA: 0x28eb0c8 VA: 0x7594f030c8
	public Void ClearSelection() { }
	// RVA: 0x28ea9b8 VA: 0x7594f029b8
	public Void SetPreviewingPlateGroup(String plateGroupId) { }
	// RVA: 0x28eb058 VA: 0x7594f03058
	public Void ClearPreviewingPlateGroup() { }
	// RVA: 0x28eadec VA: 0x7594f02dec
	public Void FillPlatePiece(PlateSlotData platePiece) { }
	// RVA: 0x28eb450 VA: 0x7594f03450
	public Void ClearFilledPlatePiece() { }
	// RVA: 0x28eac18 VA: 0x7594f02c18
	public Int32 GetPlateSlotFilledIndex(PlateSlotData plateSlot) { }
	// RVA: 0x28ead18 VA: 0x7594f02d18
	public Int32 GetFirstEmptyPlateSlotIndex() { }
	// RVA: 0x28eee28 VA: 0x7594f06e28
	public Int32 GetPlateGroupFilledCount(String groupId) { }
	// RVA: 0x28eef74 VA: 0x7594f06f74
	public Void GenNotNullFilledPlateList(List`1 outputList) { }
	// RVA: 0x28ed1d0 VA: 0x7594f051d0
	public Int32 GetFilledCount() { }
	// RVA: 0x28ef0f8 VA: 0x7594f070f8
	public Boolean IsLastPlateValid() { }
	// RVA: 0x28ef230 VA: 0x7594f07230
	public Boolean IsAllEquipPlateValid() { }
	// RVA: 0x28ef350 VA: 0x7594f07350
	public Void .ctor() { }
}
```