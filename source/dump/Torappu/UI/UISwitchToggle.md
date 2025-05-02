# UISwitchToggle

**Namespace:** `Torappu.UI`


## Fields

- `Graphic _offImage`

- `Graphic _onImage`

- `Toggle m_toggle`


## Properties

- `Toggle toggle`


## Methods

- `Toggle get_toggle()`

- `Void _OnToggled(Boolean)`

- `Void _InitToggle()`

- `Void UpdateImages()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISwitchToggle : MonoBehaviour, IHotfixable
{
	private Graphic _offImage; // 0x18
	private Graphic _onImage; // 0x20
	private Toggle m_toggle; // 0x28
	private static DelegateBridge __Hotfix0_get_toggle; // 0x0
	private static DelegateBridge __Hotfix0_get_isOn; // 0x8
	private static DelegateBridge __Hotfix0_set_isOn; // 0x10
	private static DelegateBridge __Hotfix0_get_interactable; // 0x18
	private static DelegateBridge __Hotfix0_SetInteractable; // 0x20
	private static DelegateBridge __Hotfix0__OnToggled; // 0x28
	private static DelegateBridge __Hotfix0__InitToggle; // 0x30
	private static DelegateBridge __Hotfix0_UpdateImages; // 0x38
	private static DelegateBridge __Hotfix0_Awake; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected Toggle toggle { get; }
	public virtual Boolean isOn { get; set; }
	public virtual Boolean interactable { get; }

	// RVA: 0x22570c0 VA: 0x759486f0c0
	protected Toggle get_toggle() { }
	// RVA: 0x22572ec VA: 0x759486f2ec
	public virtual Boolean get_isOn() { }
	// RVA: 0x2257364 VA: 0x759486f364
	public virtual Void set_isOn(Boolean value) { }
	// RVA: 0x2257530 VA: 0x759486f530
	public virtual Boolean get_interactable() { }
	// RVA: 0x22575a8 VA: 0x759486f5a8
	public virtual Void SetInteractable(Boolean val, Boolean force) { }
	// RVA: 0x2257640 VA: 0x759486f640
	private Void _OnToggled(Boolean isOn) { }
	// RVA: 0x225716c VA: 0x759486f16c
	private Void _InitToggle() { }
	// RVA: 0x225742c VA: 0x759486f42c
	protected Void UpdateImages() { }
	// RVA: 0x22576bc VA: 0x759486f6bc
	private Void Awake() { }
	// RVA: 0x225772c VA: 0x759486f72c
	public Void .ctor() { }
}
```