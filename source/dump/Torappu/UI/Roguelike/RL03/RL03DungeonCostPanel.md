# RL03DungeonCostPanel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `Action onCancel`

- `Action onAccept`

- `CanvasGroup _canvas`

- `Text _itemCount`

- `Text _itemRemainContainer`

- `UIColorGraphic _uiColor`

- `GameObject _minPart`

- `GameObject _maxPart`

- `GameObject _commonPart`

- `GameObject _minText`

- `FadeSwitchTween m_showTween`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void _OpenPanel()`

- `Void _ClosePanel()`

- `Void EventOnConfirm()`

- `Void OnCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03DungeonCostPanel : RoguelikeDungeonCostBasePanel
{
	public Action onCancel; // 0x18
	public Action onAccept; // 0x20
	private CanvasGroup _canvas; // 0x28
	private Text _itemCount; // 0x30
	private Text _itemRemainContainer; // 0x38
	private UIColorGraphic _uiColor; // 0x40
	private GameObject _minPart; // 0x48
	private GameObject _maxPart; // 0x50
	private GameObject _commonPart; // 0x58
	private GameObject _minText; // 0x60
	private FadeSwitchTween m_showTween; // 0x68
	private Boolean m_inited; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_HandleOnOpenCost; // 0x8
	private static DelegateBridge __Hotfix0__OpenPanel; // 0x10
	private static DelegateBridge __Hotfix0__ClosePanel; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x20
	private static DelegateBridge __Hotfix0_OnCancel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2b8a770 VA: 0x75951a2770
	private Void _InitIfNot() { }
	// RVA: 0x2b8a854 VA: 0x75951a2854
	public override Void HandleOnOpenCost(UIPage page, Config config) { }
	// RVA: 0x2b8aaa8 VA: 0x75951a2aa8
	private Void _OpenPanel() { }
	// RVA: 0x2b8ab20 VA: 0x75951a2b20
	private Void _ClosePanel() { }
	// RVA: 0x2b8ab98 VA: 0x75951a2b98
	public Void EventOnConfirm() { }
	// RVA: 0x2b8ac18 VA: 0x75951a2c18
	public Void OnCancel() { }
	// RVA: 0x2b8ac98 VA: 0x75951a2c98
	public Void .ctor() { }
}
```