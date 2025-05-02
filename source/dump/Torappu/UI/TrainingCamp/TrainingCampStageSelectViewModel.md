# TrainingCampStageSelectViewModel

**Namespace:** `Torappu.UI.TrainingCamp`


## Fields

- `Int32 <selectIndex>k__BackingField`

- `Int32 <firstAvailIndex>k__BackingField`

- `Int32 <doneCnt>k__BackingField`

- `Int32 <totalCnt>k__BackingField`

- `String <updateDesc>k__BackingField`

- `ItemBundle <rewardItemBundle>k__BackingField`

- `Int32 <focusSeqNum>k__BackingField`


## Properties

- `Int32 selectIndex`

- `Int32 firstAvailIndex`

- `Int32 doneCnt`

- `Int32 totalCnt`

- `String updateDesc`

- `ItemBundle rewardItemBundle`

- `Int32 focusSeqNum`


## Methods

- `Int32 get_selectIndex()`

- `Void set_selectIndex(Int32)`

- `Int32 get_firstAvailIndex()`

- `Void set_firstAvailIndex(Int32)`

- `Int32 get_doneCnt()`

- `Void set_doneCnt(Int32)`

- `Int32 get_totalCnt()`

- `Void set_totalCnt(Int32)`

- `String get_updateDesc()`

- `Void set_updateDesc(String)`

- `ItemBundle get_rewardItemBundle()`

- `Void set_rewardItemBundle(ItemBundle)`

- `Int32 get_focusSeqNum()`

- `Void set_focusSeqNum(Int32)`

- `Void LoadData()`

- `Void SelectStageById(String)`

- `Void SelectStage(Int32)`

- `Void FocusToSelectIdx()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TrainingCamp
public class TrainingCampStageSelectViewModel : IHotfixable
{
	public List`1 stageListItemViewModels; // 0x10
	private Int32 <selectIndex>k__BackingField; // 0x18
	private Int32 <firstAvailIndex>k__BackingField; // 0x1c
	private Int32 <doneCnt>k__BackingField; // 0x20
	private Int32 <totalCnt>k__BackingField; // 0x24
	private String <updateDesc>k__BackingField; // 0x28
	private ItemBundle <rewardItemBundle>k__BackingField; // 0x30
	private Int32 <focusSeqNum>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_selectIndex; // 0x0
	private static DelegateBridge __Hotfix0_set_selectIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_firstAvailIndex; // 0x10
	private static DelegateBridge __Hotfix0_set_firstAvailIndex; // 0x18
	private static DelegateBridge __Hotfix0_get_doneCnt; // 0x20
	private static DelegateBridge __Hotfix0_set_doneCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_totalCnt; // 0x30
	private static DelegateBridge __Hotfix0_set_totalCnt; // 0x38
	private static DelegateBridge __Hotfix0_get_updateDesc; // 0x40
	private static DelegateBridge __Hotfix0_set_updateDesc; // 0x48
	private static DelegateBridge __Hotfix0_get_rewardItemBundle; // 0x50
	private static DelegateBridge __Hotfix0_set_rewardItemBundle; // 0x58
	private static DelegateBridge __Hotfix0_get_focusSeqNum; // 0x60
	private static DelegateBridge __Hotfix0_set_focusSeqNum; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x70
	private static DelegateBridge __Hotfix0_SelectStageById; // 0x78
	private static DelegateBridge __Hotfix0_SelectStage; // 0x80
	private static DelegateBridge __Hotfix0_FocusToSelectIdx; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public Int32 selectIndex { get; set; }
	public Int32 firstAvailIndex { get; set; }
	public Int32 doneCnt { get; set; }
	public Int32 totalCnt { get; set; }
	public String updateDesc { get; set; }
	public ItemBundle rewardItemBundle { get; set; }
	public Int32 focusSeqNum { get; set; }

	// RVA: 0x234b840 VA: 0x7594963840
	public Int32 get_selectIndex() { }
	// RVA: 0x234cf8c VA: 0x7594964f8c
	private Void set_selectIndex(Int32 value) { }
	// RVA: 0x234ad80 VA: 0x7594962d80
	public Int32 get_firstAvailIndex() { }
	// RVA: 0x234d008 VA: 0x7594965008
	private Void set_firstAvailIndex(Int32 value) { }
	// RVA: 0x234c670 VA: 0x7594964670
	public Int32 get_doneCnt() { }
	// RVA: 0x234d084 VA: 0x7594965084
	private Void set_doneCnt(Int32 value) { }
	// RVA: 0x234c6d8 VA: 0x75949646d8
	public Int32 get_totalCnt() { }
	// RVA: 0x234d100 VA: 0x7594965100
	private Void set_totalCnt(Int32 value) { }
	// RVA: 0x234d17c VA: 0x759496517c
	public String get_updateDesc() { }
	// RVA: 0x234d1e4 VA: 0x75949651e4
	private Void set_updateDesc(String value) { }
	// RVA: 0x234ce54 VA: 0x7594964e54
	public ItemBundle get_rewardItemBundle() { }
	// RVA: 0x234d268 VA: 0x7594965268
	private Void set_rewardItemBundle(ItemBundle value) { }
	// RVA: 0x234cdec VA: 0x7594964dec
	public Int32 get_focusSeqNum() { }
	// RVA: 0x234d2ec VA: 0x75949652ec
	private Void set_focusSeqNum(Int32 value) { }
	// RVA: 0x234a734 VA: 0x7594962734
	public Void LoadData() { }
	// RVA: 0x234af58 VA: 0x7594962f58
	public Void SelectStageById(String stageId) { }
	// RVA: 0x234ade8 VA: 0x7594962de8
	public Void SelectStage(Int32 index) { }
	// RVA: 0x234b07c VA: 0x759496307c
	public Void FocusToSelectIdx() { }
	// RVA: 0x234d5f4 VA: 0x75949655f4
	public Void .ctor() { }
}
```