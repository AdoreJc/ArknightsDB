# CheckboxController

**Namespace:** ` `


## Fields

- `GameObject m_panelCheckbox`

- `Text m_textCheckbox`

- `TwoStateToggle m_toggleCheckbox`

- `Boolean <isCheck>k__BackingField`


## Properties

- `Boolean isCheck`


## Methods

- `Boolean get_isCheck()`

- `Void set_isCheck(Boolean)`

- `Void Render(CheckboxConfig)`

- `Boolean ToggleCheckStatus()`

- `Void _SetCheckStatus(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class CheckboxController : IHotfixable
{
	private GameObject m_panelCheckbox; // 0x10
	private Text m_textCheckbox; // 0x18
	private TwoStateToggle m_toggleCheckbox; // 0x20
	private Boolean <isCheck>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_isCheck; // 0x0
	private static DelegateBridge __Hotfix0_set_isCheck; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_ToggleCheckStatus; // 0x20
	private static DelegateBridge __Hotfix0__SetCheckStatus; // 0x28

	public Boolean isCheck { get; set; }

	// RVA: 0x2217304 VA: 0x759482f304
	public Boolean get_isCheck() { }
	// RVA: 0x221736c VA: 0x759482f36c
	private Void set_isCheck(Boolean value) { }
	// RVA: 0x22173ec VA: 0x759482f3ec
	public Void .ctor(UIJudgeDialog closure) { }
	// RVA: 0x221749c VA: 0x759482f49c
	public Void Render(CheckboxConfig config) { }
	// RVA: 0x2217624 VA: 0x759482f624
	public Boolean ToggleCheckStatus() { }
	// RVA: 0x2217588 VA: 0x759482f588
	private Void _SetCheckStatus(Boolean isCheck) { }
}
```