# RL04NodeUpgradeTypeItemView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `Text _textName`

- `Image _imgSelect`

- `Image _imgUnselect`

- `GameObject _selectPartGo`

- `GameObject _unselectPartGo`

- `RoguelikeEventType m_nodeType`


## Methods

- `Void set_onClick(Action`1)`

- `Void Render(RL04NodeUpgradeModel, RL04NodeUpgradeConfig, Boolean)`

- `Void EventOnBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04NodeUpgradeTypeItemView : MonoBehaviour, IHotfixable
{
	private Text _textName; // 0x18
	private Image _imgSelect; // 0x20
	private Image _imgUnselect; // 0x28
	private GameObject _selectPartGo; // 0x30
	private GameObject _unselectPartGo; // 0x38
	private RoguelikeEventType m_nodeType; // 0x40
	private Action`1 <onClick>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBtnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onClick { get; set; }

	// RVA: 0x26e80e4 VA: 0x7594d000e4
	private Action`1 get_onClick() { }
	// RVA: 0x26e7ed8 VA: 0x7594cffed8
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x26e7f5c VA: 0x7594cfff5c
	public Void Render(RL04NodeUpgradeModel upgradeModel, RL04NodeUpgradeConfig currNodeConfig, Boolean isSelect) { }
	// RVA: 0x26e814c VA: 0x7594d0014c
	public Void EventOnBtnClick() { }
	// RVA: 0x26e81ec VA: 0x7594d001ec
	public Void .ctor() { }
}
```