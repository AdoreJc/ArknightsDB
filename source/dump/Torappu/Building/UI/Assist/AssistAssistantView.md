# AssistAssistantView

**Namespace:** `Torappu.Building.UI.Assist`


## Fields

- `GameObject _charObj`

- `GameObject _noCharObj`

- `GameObject _lockedObj`

- `UIAtlasImage _charPortrait`

- `Text _lockText`

- `Text _storeyText`

- `Text _textFavor`

- `GameObject _panelFavor`

- `GameObject _trackPoint`

- `Int32 m_currentIndex`

- `Int32 m_charInstId`


## Methods

- `Void set_onAssistViewClicked(Action`1)`

- `Void Render(Int32, Int32)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Assist
public class AssistAssistantView : MonoBehaviour, IHotfixable
{
	private GameObject _charObj; // 0x18
	private GameObject _noCharObj; // 0x20
	private GameObject _lockedObj; // 0x28
	private UIAtlasImage _charPortrait; // 0x30
	private Text _lockText; // 0x38
	private Text _storeyText; // 0x40
	private Text _textFavor; // 0x48
	private GameObject _panelFavor; // 0x50
	private GameObject _trackPoint; // 0x58
	private Action`1 <onAssistViewClicked>k__BackingField; // 0x60
	private Int32 m_currentIndex; // 0x68
	private Int32 m_charInstId; // 0x6c
	private static DelegateBridge __Hotfix0_get_onAssistViewClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onAssistViewClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onAssistViewClicked { get; set; }

	// RVA: 0x3e336a8 VA: 0x759644b6a8
	private Action`1 get_onAssistViewClicked() { }
	// RVA: 0x3e332f8 VA: 0x759644b2f8
	public Void set_onAssistViewClicked(Action`1 value) { }
	// RVA: 0x3e32c20 VA: 0x759644ac20
	public Void Render(Int32 index, Int32 charInstId) { }
	// RVA: 0x3e33710 VA: 0x759644b710
	public Void OnClick() { }
	// RVA: 0x3e337b0 VA: 0x759644b7b0
	public Void .ctor() { }
}
```