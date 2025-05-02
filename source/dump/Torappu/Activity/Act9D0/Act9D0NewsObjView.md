# Act9D0NewsObjView

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Image _newsLogo`

- `Image _newsImg`

- `GameObject _unread`

- `Text _newsTitle`

- `Text _newsContent`

- `Text _constText`

- `GameObject _chosenObj`

- `Color _lightColor`

- `Color _darkColor`

- `String m_newsId`

- `UIStringEvent <onClicked>k__BackingField`


## Properties

- `UIStringEvent onClicked`


## Methods

- `UIStringEvent get_onClicked()`

- `Void set_onClicked(UIStringEvent)`

- `Void Render(Act9D0NewsViewModel, String, String)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0NewsObjView : MonoBehaviour, IHotfixable
{
	private Image _newsLogo; // 0x18
	private Image _newsImg; // 0x20
	private GameObject _unread; // 0x28
	private Text _newsTitle; // 0x30
	private Text _newsContent; // 0x38
	private Text _constText; // 0x40
	private GameObject _chosenObj; // 0x48
	private Color _lightColor; // 0x50
	private Color _darkColor; // 0x60
	private String m_newsId; // 0x70
	private UIStringEvent <onClicked>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public UIStringEvent onClicked { get; set; }

	// RVA: 0x31a9454 VA: 0x75957c1454
	public UIStringEvent get_onClicked() { }
	// RVA: 0x31a90cc VA: 0x75957c10cc
	public Void set_onClicked(UIStringEvent value) { }
	// RVA: 0x31a9150 VA: 0x75957c1150
	public Void Render(Act9D0NewsViewModel model, String chosenId, String actId) { }
	// RVA: 0x31a94cc VA: 0x75957c14cc
	public Void EventOnClicked() { }
	// RVA: 0x31a9574 VA: 0x75957c1574
	public Void .ctor() { }
}
```