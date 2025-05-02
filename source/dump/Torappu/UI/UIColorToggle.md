# UIColorToggle

**Namespace:** `Torappu.UI`


## Fields

- `Graphic _target`

- `Color _onColor`

- `Color _offColor`

- `Single _duration`

- `Graphic m_target`

- `Boolean m_isOn`


## Properties

- `Boolean isOn`


## Methods

- `Boolean get_isOn()`

- `Void set_isOn(Boolean)`

- `Void SetTarget(Graphic)`

- `Void _InitIfNot()`

- `Void UpdateImages()`

- `Void Awake()`

- `Void OnEnable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIColorToggle : MonoBehaviour, IHotfixable
{
	private Graphic _target; // 0x18
	private Color _onColor; // 0x20
	private Color _offColor; // 0x30
	private Single _duration; // 0x40
	private Graphic m_target; // 0x48
	private Boolean m_isOn; // 0x50
	private static DelegateBridge __Hotfix0_get_isOn; // 0x0
	private static DelegateBridge __Hotfix0_set_isOn; // 0x8
	private static DelegateBridge __Hotfix0_SetTarget; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_UpdateImages; // 0x20
	private static DelegateBridge __Hotfix0_Awake; // 0x28
	private static DelegateBridge __Hotfix0_OnEnable; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isOn { get; set; }

	// RVA: 0x22434e8 VA: 0x759485b4e8
	public Boolean get_isOn() { }
	// RVA: 0x2243550 VA: 0x759485b550
	public Void set_isOn(Boolean value) { }
	// RVA: 0x22436fc VA: 0x759485b6fc
	public Void SetTarget(Graphic target) { }
	// RVA: 0x22437d8 VA: 0x759485b7d8
	private Void _InitIfNot() { }
	// RVA: 0x22435f4 VA: 0x759485b5f4
	protected Void UpdateImages() { }
	// RVA: 0x224389c VA: 0x759485b89c
	private Void Awake() { }
	// RVA: 0x2243904 VA: 0x759485b904
	private Void OnEnable() { }
	// RVA: 0x224396c VA: 0x759485b96c
	public Void .ctor() { }
}
```