# MultiStateToggleGroup

**Namespace:** `Torappu.UI`


## Fields

- `StateChangedEvent _onStateChanged`

- `MultiStateToggle m_selected`


## Properties

- `String selectedStateID`


## Methods

- `Void Awake()`

- `String get_selectedStateID()`

- `Void set_selectedStateID(String)`

- `Void _HandleSelectChanged(MultiStateToggle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class MultiStateToggleGroup : MonoBehaviour, IHotfixable
{
	private StateChangedEvent _onStateChanged; // 0x18
	private MultiStateToggle[] m_toggles; // 0x20
	private MultiStateToggle m_selected; // 0x28
	public Action`1 eStateChanged; // 0x30
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedStateID; // 0x8
	private static DelegateBridge __Hotfix0_set_selectedStateID; // 0x10
	private static DelegateBridge __Hotfix0__HandleSelectChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String selectedStateID { get; set; }

	// RVA: 0x2235dcc VA: 0x759484ddcc
	private Void Awake() { }
	// RVA: 0x2235fb0 VA: 0x759484dfb0
	public String get_selectedStateID() { }
	// RVA: 0x2236088 VA: 0x759484e088
	public Void set_selectedStateID(String value) { }
	// RVA: 0x2236168 VA: 0x759484e168
	private Void _HandleSelectChanged(MultiStateToggle toggle) { }
	// RVA: 0x22362c0 VA: 0x759484e2c0
	public Void .ctor() { }
}
```