# CommonCharSelectPoolViewModel

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `TemplateCharSelectCardViewModel m_lastSelectChar`

- `TemplateCharSelectMode <selectMode>k__BackingField`

- `Boolean ensured`

- `Int32 focusSeqNun`

- `Int32 <focusIndex>k__BackingField`

- `InputParam m_cacheInput`


## Properties

- `TemplateCharSelectMode selectMode`

- `Boolean isSingle`

- `Int32 focusIndex`


## Methods

- `TemplateCharSelectMode get_selectMode()`

- `Void set_selectMode(TemplateCharSelectMode)`

- `Boolean get_isSingle()`

- `Int32 get_focusIndex()`

- `Void set_focusIndex(Int32)`

- `Void set_shuffleResult(List`1)`

- `Void _AddToCharCollection(TemplateCharSelectCardViewModel, Boolean)`

- `Boolean _DoSingleSelect(Int32)`

- `Boolean _DoMultiSelect(Int32)`

- `TemplateCharSelectCardViewModel GetCharViewModelByInstId(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectPoolViewModel : TemplateCharSelectPoolViewModel
{
	public Dictionary`2 charDict; // 0x10
	public List`1 charList; // 0x18
	public List`1 selectedList; // 0x20
	public Dictionary`2 selectedDict; // 0x28
	public List`1 selectedInsts; // 0x30
	protected TemplateCharSelectCardViewModel m_lastSelectChar; // 0x38
	private TemplateCharSelectMode <selectMode>k__BackingField; // 0x40
	public Boolean ensured; // 0x44
	public Int32 focusSeqNun; // 0x48
	private Int32 <focusIndex>k__BackingField; // 0x4c
	private List`1 <shuffleResult>k__BackingField; // 0x50
	protected InputParam m_cacheInput; // 0x58
	private static DelegateBridge __Hotfix0_get_selectedCharList; // 0x0
	private static DelegateBridge __Hotfix0_get_lastSelectedChar; // 0x8
	private static DelegateBridge __Hotfix0_get_selectMode; // 0x10
	private static DelegateBridge __Hotfix0_set_selectMode; // 0x18
	private static DelegateBridge __Hotfix0_get_isSingle; // 0x20
	private static DelegateBridge __Hotfix0_get_focusIndex; // 0x28
	private static DelegateBridge __Hotfix0_set_focusIndex; // 0x30
	private static DelegateBridge __Hotfix0_get_shuffleResult; // 0x38
	private static DelegateBridge __Hotfix0_set_shuffleResult; // 0x40
	private static DelegateBridge __Hotfix0_Reset; // 0x48
	private static DelegateBridge __Hotfix0_Resume; // 0x50
	private static DelegateBridge __Hotfix0__AddToCharCollection; // 0x58
	private static DelegateBridge __Hotfix0_SelectChar; // 0x60
	private static DelegateBridge __Hotfix0__DoSingleSelect; // 0x68
	private static DelegateBridge __Hotfix0__DoMultiSelect; // 0x70
	private static DelegateBridge __Hotfix0_ClearAllSelect; // 0x78
	private static DelegateBridge __Hotfix0_GetCharViewModelByInstId; // 0x80
	private static DelegateBridge __Hotfix0_ApplyShuffle; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public override List`1 selectedCharList { get; }
	public override TemplateCharSelectCardViewModel lastSelectedChar { get; }
	public TemplateCharSelectMode selectMode { get; set; }
	public Boolean isSingle { get; }
	public Int32 focusIndex { get; set; }
	public List`1 shuffleResult { get; set; }

	// RVA: 0x2c59284 VA: 0x7595271284
	public override List`1 get_selectedCharList() { }
	// RVA: 0x2c592ec VA: 0x75952712ec
	public override TemplateCharSelectCardViewModel get_lastSelectedChar() { }
	// RVA: 0x2c59354 VA: 0x7595271354
	public TemplateCharSelectMode get_selectMode() { }
	// RVA: 0x2c593bc VA: 0x75952713bc
	protected Void set_selectMode(TemplateCharSelectMode value) { }
	// RVA: 0x2c59438 VA: 0x7595271438
	public Boolean get_isSingle() { }
	// RVA: 0x2c594ac VA: 0x75952714ac
	public Int32 get_focusIndex() { }
	// RVA: 0x2c59514 VA: 0x7595271514
	protected Void set_focusIndex(Int32 value) { }
	// RVA: 0x2c59590 VA: 0x7595271590
	public List`1 get_shuffleResult() { }
	// RVA: 0x2c595f8 VA: 0x75952715f8
	protected Void set_shuffleResult(List`1 value) { }
	// RVA: 0x2c5967c VA: 0x759527167c
	public override Void Reset(TemplateCharSelectModelResetData data) { }
	// RVA: 0x2c59f08 VA: 0x7595271f08
	public override Void Resume() { }
	// RVA: 0x2c59cac VA: 0x7595271cac
	protected Void _AddToCharCollection(TemplateCharSelectCardViewModel charModel, Boolean canSelect) { }
	// RVA: 0x2c59fa4 VA: 0x7595271fa4
	public override Boolean SelectChar(Int32 instId) { }
	// RVA: 0x2c5a190 VA: 0x7595272190
	private Boolean _DoSingleSelect(Int32 instId) { }
	// RVA: 0x2c5a3b0 VA: 0x75952723b0
	private Boolean _DoMultiSelect(Int32 instId) { }
	// RVA: 0x2c5a6e8 VA: 0x75952726e8
	public override Void ClearAllSelect() { }
	// RVA: 0x2c5a5c0 VA: 0x75952725c0
	protected TemplateCharSelectCardViewModel GetCharViewModelByInstId(Int32 instId) { }
	// RVA: 0x2c5a864 VA: 0x7595272864
	public sealed override Void ApplyShuffle(TemplateCharSelectShuffleViewModel shuffleViewModel) { }
	// RVA: 0x2c5ab28 VA: 0x7595272b28
	public Void .ctor() { }
}
```