# VoicelangCardGroupViewModel

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `CardGroupFilterType m_groupFilterType`

- `CardPowerFilterType m_powerFilterType`

- `String m_lastSelectedWordkey`

- `SelectState m_selectState`

- `Boolean skipFilterAndSort`


## Methods

- `Void set_dataSource(Dictionary`2)`

- `Void SetSingleSelect(String)`

- `Void SetBatchSelect()`

- `Void CancelSelect()`

- `Void RefreshCardsVoicelangType()`

- `Void RefreshRedPoint()`

- `Void SetCardTargetVoiceTypeToSwitch(VoiceLangType)`

- `Void SetVoicelangGroupType(Boolean, VoiceLangGroupType)`

- `Void SetPower(Boolean, String)`

- `Int32 <_AchieveSortedAndFilteredCards>b__23_0(VoicelangCardViewModel, VoicelangCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangCardGroupViewModel
{
	private Dictionary`2 m_cardViewModels; // 0x10
	private List`1 m_cardListCache; // 0x18
	private CardGroupFilterType m_groupFilterType; // 0x20
	private CardPowerFilterType m_powerFilterType; // 0x28
	private String m_lastSelectedWordkey; // 0x38
	private SelectState m_selectState; // 0x40
	private Boolean skipFilterAndSort; // 0x44

	public Dictionary`2 dataSource { get; set; }
	public List`1 cardList { get; }

	// RVA: 0x2298bec VA: 0x75948b0bec
	public Void set_dataSource(Dictionary`2 value) { }
	// RVA: 0x2298c10 VA: 0x75948b0c10
	public Dictionary`2 get_dataSource() { }
	// RVA: 0x2298c18 VA: 0x75948b0c18
	public List`1 get_cardList() { }
	// RVA: 0x2299190 VA: 0x75948b1190
	public Void SetSingleSelect(String selectedWordkey) { }
	// RVA: 0x2299584 VA: 0x75948b1584
	public Void SetBatchSelect() { }
	// RVA: 0x2299408 VA: 0x75948b1408
	public Void CancelSelect() { }
	// RVA: 0x22995a0 VA: 0x75948b15a0
	public Void RefreshCardsVoicelangType() { }
	// RVA: 0x229990c VA: 0x75948b190c
	public Void RefreshRedPoint() { }
	// RVA: 0x2299bb8 VA: 0x75948b1bb8
	public List`1 GetNewVoiceCardListWithVoicelangGroupTypeFiltered() { }
	// RVA: 0x2297d1c VA: 0x75948afd1c
	public List`1 GetSelectedList() { }
	// RVA: 0x229925c VA: 0x75948b125c
	public Void SetCardTargetVoiceTypeToSwitch(VoiceLangType targetType) { }
	// RVA: 0x229a140 VA: 0x75948b2140
	public Void SetVoicelangGroupType(Boolean isAll, VoiceLangGroupType groupType) { }
	// RVA: 0x229a398 VA: 0x75948b2398
	public Void SetPower(Boolean isAll, String powerId) { }
	// RVA: 0x2298c58 VA: 0x75948b0c58
	private List`1 _AchieveSortedAndFilteredCards() { }
	// RVA: 0x229a438 VA: 0x75948b2438
	public Void .ctor() { }
	// RVA: 0x229a55c VA: 0x75948b255c
	private Int32 <_AchieveSortedAndFilteredCards>b__23_0(VoicelangCardViewModel a, VoicelangCardViewModel b) { }
}
```