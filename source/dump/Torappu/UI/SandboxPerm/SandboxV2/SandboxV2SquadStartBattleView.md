# SandboxV2SquadStartBattleView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAtlasImage _imgMiniSquadBar`

- `UIAtlasImage _imgLargeSquadBar`

- `Color _colorSlotEmpty`

- `Color _colorSlotUsed`

- `Color _colorSlotNormal`

- `Color _colorBarEnable`

- `Color _colorBarDisable`

- `Text _textDrinkCost`

- `Text _textDrinkTotal`

- `GameObject _drinkCostBgNormalGo`

- `GameObject _drinkCostBgLackGo`

- `Image _imgDrinkIcon`

- `GameObject _drinkCostGo`

- `GameObject _btnStartBattleGo`

- `GameObject _panelMonthTips`

- `GameObject _panelDrink`

- `GameObject _panelApCost`

- `GameObject _panelNormalBtnStartBattle`

- `GameObject _panelMonthBtnStartBattle`

- `UIStateFinder m_stateFinder`

- `Boolean m_hasInit`


## Methods

- `Color _GetBarColor(Boolean)`

- `Void _InitIfNot()`

- `Void _RegisterTutorialGo()`

- `Color _GetSlotColor(SandboxV2SlotStatus)`

- `Void EventOnBtnStart()`

- `Void EventOnBtnMakeDrink()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadStartBattleView : DataBinder`1
{
	private UIAtlasImage[] _iconSlotList; // 0x20
	private UIAtlasImage _imgMiniSquadBar; // 0x28
	private UIAtlasImage _imgLargeSquadBar; // 0x30
	private Color _colorSlotEmpty; // 0x38
	private Color _colorSlotUsed; // 0x48
	private Color _colorSlotNormal; // 0x58
	private Color _colorBarEnable; // 0x68
	private Color _colorBarDisable; // 0x78
	private Text _textDrinkCost; // 0x88
	private Text _textDrinkTotal; // 0x90
	private GameObject _drinkCostBgNormalGo; // 0x98
	private GameObject _drinkCostBgLackGo; // 0xa0
	private Image _imgDrinkIcon; // 0xa8
	private GameObject _drinkCostGo; // 0xb0
	private GameObject _btnStartBattleGo; // 0xb8
	private GameObject _panelMonthTips; // 0xc0
	private GameObject _panelDrink; // 0xc8
	private GameObject _panelApCost; // 0xd0
	private GameObject _panelNormalBtnStartBattle; // 0xd8
	private GameObject _panelMonthBtnStartBattle; // 0xe0
	private UIStateFinder m_stateFinder; // 0xe8
	private Boolean m_hasInit; // 0xf8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__GetBarColor; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x18
	private static DelegateBridge __Hotfix0__GetSlotColor; // 0x20
	private static DelegateBridge __Hotfix0_EventOnBtnStart; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBtnMakeDrink; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x261b980 VA: 0x7594c33980
	public override Void OnValueChanged(SandboxV2SquadGroupProp property) { }
	// RVA: 0x261bebc VA: 0x7594c33ebc
	private Color _GetBarColor(Boolean isActive) { }
	// RVA: 0x261bd98 VA: 0x7594c33d98
	private Void _InitIfNot() { }
	// RVA: 0x261bf44 VA: 0x7594c33f44
	private Void _RegisterTutorialGo() { }
	// RVA: 0x261be1c VA: 0x7594c33e1c
	private Color _GetSlotColor(SandboxV2SlotStatus slotStatus) { }
	// RVA: 0x261c060 VA: 0x7594c34060
	public Void EventOnBtnStart() { }
	// RVA: 0x261c104 VA: 0x7594c34104
	public Void EventOnBtnMakeDrink() { }
	// RVA: 0x261c1a8 VA: 0x7594c341a8
	public Void .ctor() { }
}
```