# RoguelikeInitRecruit

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `RectTransform _contentRoot`

- `GameObject _recruitNode`

- `Text _titleText`

- `Text _descText`

- `Image _iconImage`

- `Image _underTexImage`

- `Button _selectButton`

- `CanvasGroup _bottomTips`

- `GameObject _enableHintObject`

- `GameObject _continueHintObject`

- `RoguelikeInitChar _charPrefab`

- `RoguelikeInitChar m_charCard`

- `Int32 m_index`


## Methods

- `Void Setup(Int32, Model)`

- `Void EventOnSelectPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitRecruit : RoguelikeInitCardBase
{
	private RectTransform _contentRoot; // 0x28
	private GameObject _recruitNode; // 0x30
	private Text _titleText; // 0x38
	private Text _descText; // 0x40
	private Image _iconImage; // 0x48
	private Image _underTexImage; // 0x50
	private Button _selectButton; // 0x58
	private CanvasGroup _bottomTips; // 0x60
	private GameObject _enableHintObject; // 0x68
	private GameObject _continueHintObject; // 0x70
	private RoguelikeInitChar _charPrefab; // 0x78
	private RoguelikeInitChar m_charCard; // 0x80
	private Int32 m_index; // 0x88
	public Action`1 selectCallback; // 0x90
	private static DelegateBridge __Hotfix0_Setup; // 0x0
	private static DelegateBridge __Hotfix0_EventOnSelectPressed; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b88074 VA: 0x75951a0074
	public Void Setup(Int32 idx, Model model) { }
	// RVA: 0x2b88458 VA: 0x75951a0458
	public Void EventOnSelectPressed() { }
	// RVA: 0x2b884e0 VA: 0x75951a04e0
	public Void .ctor() { }
}
```