# HotUpdateNetErrorAlert

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `Text _textError`

- `Text _textDesc`

- `Text _textButton`

- `NetworkErrorDisplayer m_controller`

- `Action <onNetCheckClicked>k__BackingField`


## Properties

- `Action onNetCheckClicked`


## Methods

- `Action get_onNetCheckClicked()`

- `Void set_onNetCheckClicked(Action)`

- `Void Init(String)`

- `Void EventOnNetCheckClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateNetErrorAlert : MonoBehaviour, IHotfixable
{
	private Text _textError; // 0x18
	private Text _textDesc; // 0x20
	private Text _textButton; // 0x28
	private NetworkErrorDisplayer m_controller; // 0x30
	private Action <onNetCheckClicked>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_onNetCheckClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onNetCheckClicked; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_EventOnNetCheckClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action onNetCheckClicked { get; set; }

	// RVA: 0x27c9474 VA: 0x7594de1474
	private Action get_onNetCheckClicked() { }
	// RVA: 0x27c94dc VA: 0x7594de14dc
	public Void set_onNetCheckClicked(Action value) { }
	// RVA: 0x27c9560 VA: 0x7594de1560
	public Void Init(String errorMsg) { }
	// RVA: 0x27c9640 VA: 0x7594de1640
	public Void EventOnNetCheckClicked() { }
	// RVA: 0x27c96dc VA: 0x7594de16dc
	public Void .ctor() { }
}
```