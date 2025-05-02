# RoguelikeDungeonCostFragmentPanel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _canvas`

- `Text _desc`

- `Image _icon`

- `Text _descItem`

- `GameObject _panelSafe`

- `GameObject _panelLimit`

- `GameObject _panelOverload`

- `FadeSwitchTween m_showTween`

- `Boolean m_inited`

- `Boolean m_haveFragment`

- `String m_itemName`

- `FragmentBagStatus m_afterBagStatus`

- `Action m_onCancel`

- `Action m_onAccept`


## Methods

- `Void _InitIfNot()`

- `Int32 _LoadRealFragmentWeight(String, Int32, Dictionary`2)`

- `Void _OpenPanel()`

- `Void _ClosePanel()`

- `Void EventOnConfirm()`

- `Void OnCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonCostFragmentPanel : RoguelikeDungeonCostBasePanel
{
	private CanvasGroup _canvas; // 0x18
	private Text _desc; // 0x20
	private Image _icon; // 0x28
	private Text _descItem; // 0x30
	private GameObject _panelSafe; // 0x38
	private GameObject _panelLimit; // 0x40
	private GameObject _panelOverload; // 0x48
	private FadeSwitchTween m_showTween; // 0x50
	private Boolean m_inited; // 0x58
	private Boolean m_haveFragment; // 0x59
	private String m_itemName; // 0x60
	private FragmentBagStatus m_afterBagStatus; // 0x68
	private Action m_onCancel; // 0x70
	private Action m_onAccept; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_HandleOnOpenCost; // 0x8
	private static DelegateBridge __Hotfix0__LoadRealFragmentWeight; // 0x10
	private static DelegateBridge __Hotfix0__OpenPanel; // 0x18
	private static DelegateBridge __Hotfix0__ClosePanel; // 0x20
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x28
	private static DelegateBridge __Hotfix0_OnCancel; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2a08b20 VA: 0x7595020b20
	private Void _InitIfNot() { }
	// RVA: 0x2a08c04 VA: 0x7595020c04
	public override Void HandleOnOpenCost(UIPage page, Config config) { }
	// RVA: 0x2a09000 VA: 0x7595021000
	private Int32 _LoadRealFragmentWeight(String fragmentId, Int32 fragmentOriginWeight, Dictionary`2 fragments) { }
	// RVA: 0x2a08f88 VA: 0x7595020f88
	private Void _OpenPanel() { }
	// RVA: 0x2a091d8 VA: 0x75950211d8
	private Void _ClosePanel() { }
	// RVA: 0x2a09250 VA: 0x7595021250
	public Void EventOnConfirm() { }
	// RVA: 0x2a0934c VA: 0x759502134c
	public Void OnCancel() { }
	// RVA: 0x2a093cc VA: 0x75950213cc
	public Void .ctor() { }
}
```