# VoicelangSettingConfirmViewModel

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `ConfirmViewState m_state`

- `VoiceLangType m_selectedType`

- `VoiceLangType m_allCardsSameType`


## Properties

- `ConfirmViewState State`

- `VoiceLangType selectedType`


## Methods

- `ConfirmViewState get_State()`

- `Void set_State(ConfirmViewState)`

- `VoiceLangType get_selectedType()`

- `Void set_selectedType(VoiceLangType)`

- `Void set_selectedCards(List`1)`

- `Boolean TryGetSingleSelection(out)`

- `Boolean GetComfirmable()`

- `Boolean IsPlayerVoiceSelected()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangSettingConfirmViewModel
{
	private ConfirmViewState m_state; // 0x10
	private VoiceLangType m_selectedType; // 0x14
	private List`1 m_selectedCards; // 0x18
	private HashSet`1 m_displayTypes; // 0x20
	private VoiceLangType m_allCardsSameType; // 0x28

	public ConfirmViewState State { get; set; }
	public VoiceLangType selectedType { get; set; }
	public List`1 selectedCards { get; set; }
	public HashSet`1 displayTypes { get; }

	// RVA: 0x229ba88 VA: 0x75948b3a88
	public ConfirmViewState get_State() { }
	// RVA: 0x229ba90 VA: 0x75948b3a90
	public Void set_State(ConfirmViewState value) { }
	// RVA: 0x229ba98 VA: 0x75948b3a98
	public VoiceLangType get_selectedType() { }
	// RVA: 0x229baa0 VA: 0x75948b3aa0
	public Void set_selectedType(VoiceLangType value) { }
	// RVA: 0x229bb98 VA: 0x75948b3b98
	public List`1 get_selectedCards() { }
	// RVA: 0x229bba0 VA: 0x75948b3ba0
	public Void set_selectedCards(List`1 value) { }
	// RVA: 0x229bedc VA: 0x75948b3edc
	public Boolean TryGetSingleSelection(out VoicelangCardViewModel cardMode) { }
	// RVA: 0x229bf94 VA: 0x75948b3f94
	public HashSet`1 get_displayTypes() { }
	// RVA: 0x229bf9c VA: 0x75948b3f9c
	public Boolean GetComfirmable() { }
	// RVA: 0x229c110 VA: 0x75948b4110
	public Boolean IsPlayerVoiceSelected() { }
	// RVA: 0x229c124 VA: 0x75948b4124
	public Void .ctor() { }
}
```