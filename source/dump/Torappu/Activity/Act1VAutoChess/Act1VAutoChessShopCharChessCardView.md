# Act1VAutoChessShopCharChessCardView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `GameObject _objBgNormal`

- `GameObject _objBgMax`

- `GameObject _objCharLevelBgEmpty`

- `GameObject _objCharLevelBgNormal`

- `GameObject _objCharLevelBgMax`

- `Image _imgChessLevel`

- `GameObject _objTagAssist`

- `GameObject _objTagBackup`

- `CanvasGroup _canvasDiyCancelBtn`

- `GameObject _objClickArea`

- `CanvasGroup _canvasSelect`

- `GameObject _normalSelect`

- `GameObject _level5Select`

- `GameObject _level6Select`

- `UIAtlasImage _imgPortrait`

- `Image _imgProfession`

- `Image _imgRarity`

- `Text _txtCharName`

- `GameObject _panelSkill`

- `Image _imgSkill`

- `GameObject _panelNoSkill`

- `GameObject _panelEquip`

- `GameObject _panelEquipEmpty`

- `Image _imgEquip`

- `GameObject _objLeftInfo`

- `Image _imgEvolveNormal`

- `Image _imgEvolveGolden`

- `Text _txtLvNormal`

- `Text _txtLvGolden`

- `Image _imgPotential`

- `GameObject _panelPotential`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `String m_cachedChessId`

- `FadeSwitchTween m_selectSwitchTween`

- `FadeSwitchTween m_cancelDiySwitchTween`


## Properties

- `GameObject objLeftInfoPart`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void set_onCancelDiyBtnClick(Action`1)`

- `GameObject get_objLeftInfoPart()`

- `Void Render(Act1VAutoChessShopCharChessCardViewModel)`

- `Void _InitIfNot()`

- `Void _RenderChessTags(Act1VAutoChessShopCharChessCardViewModel)`

- `Void _RenderChessLevel(Int32)`

- `Void _SetSelectType(Int32)`

- `Void _RenderCharCardInfo(Act1VAutoChessShopCharChessCardViewModel)`

- `Void OnCardClick()`

- `Void OnDiyCancelClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessShopCharChessCardView : MonoBehaviour, IHotfixable
{
	private GameObject _objBgNormal; // 0x18
	private GameObject _objBgMax; // 0x20
	private GameObject _objCharLevelBgEmpty; // 0x28
	private GameObject _objCharLevelBgNormal; // 0x30
	private GameObject _objCharLevelBgMax; // 0x38
	private Image _imgChessLevel; // 0x40
	private GameObject _objTagAssist; // 0x48
	private GameObject _objTagBackup; // 0x50
	private CanvasGroup _canvasDiyCancelBtn; // 0x58
	private GameObject _objClickArea; // 0x60
	private CanvasGroup _canvasSelect; // 0x68
	private GameObject _normalSelect; // 0x70
	private GameObject _level5Select; // 0x78
	private GameObject _level6Select; // 0x80
	private UIAtlasImage _imgPortrait; // 0x88
	private Image _imgProfession; // 0x90
	private Image _imgRarity; // 0x98
	private Text _txtCharName; // 0xa0
	private GameObject _panelSkill; // 0xa8
	private Image _imgSkill; // 0xb0
	private GameObject _panelNoSkill; // 0xb8
	private GameObject _panelEquip; // 0xc0
	private GameObject _panelEquipEmpty; // 0xc8
	private Image _imgEquip; // 0xd0
	private GameObject _objLeftInfo; // 0xd8
	private Image _imgEvolveNormal; // 0xe0
	private Image _imgEvolveGolden; // 0xe8
	private Text _txtLvNormal; // 0xf0
	private Text _txtLvGolden; // 0xf8
	private Image _imgPotential; // 0x100
	private GameObject _panelPotential; // 0x108
	private Boolean m_hasInited; // 0x110
	private UIPageFinder m_pageFinder; // 0x118
	private String m_cachedChessId; // 0x128
	private FadeSwitchTween m_selectSwitchTween; // 0x130
	private FadeSwitchTween m_cancelDiySwitchTween; // 0x138
	private Action`1 <onItemClick>k__BackingField; // 0x140
	private Action`1 <onCancelDiyBtnClick>k__BackingField; // 0x148
	private const Int32 CHESS_LEVEL_5; // 0x0
	private const Int32 CHESS_LEVEL_6; // 0x0
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onCancelDiyBtnClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onCancelDiyBtnClick; // 0x18
	private static DelegateBridge __Hotfix0_get_objLeftInfoPart; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__RenderChessTags; // 0x38
	private static DelegateBridge __Hotfix0__RenderChessLevel; // 0x40
	private static DelegateBridge __Hotfix0__SetSelectType; // 0x48
	private static DelegateBridge __Hotfix0__RenderCharCardInfo; // 0x50
	private static DelegateBridge __Hotfix0_OnCardClick; // 0x58
	private static DelegateBridge __Hotfix0_OnDiyCancelClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Action`1 onItemClick { get; set; }
	public Action`1 onCancelDiyBtnClick { get; set; }
	public GameObject objLeftInfoPart { get; }

	// RVA: 0x3308ba8 VA: 0x7595920ba8
	public Action`1 get_onItemClick() { }
	// RVA: 0x3308c10 VA: 0x7595920c10
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x3308c94 VA: 0x7595920c94
	public Action`1 get_onCancelDiyBtnClick() { }
	// RVA: 0x3308cfc VA: 0x7595920cfc
	public Void set_onCancelDiyBtnClick(Action`1 value) { }
	// RVA: 0x3308d80 VA: 0x7595920d80
	public GameObject get_objLeftInfoPart() { }
	// RVA: 0x3308de8 VA: 0x7595920de8
	public Void Render(Act1VAutoChessShopCharChessCardViewModel viewModel) { }
	// RVA: 0x3308f38 VA: 0x7595920f38
	private Void _InitIfNot() { }
	// RVA: 0x3309064 VA: 0x7595921064
	private Void _RenderChessTags(Act1VAutoChessShopCharChessCardViewModel viewModel) { }
	// RVA: 0x33091dc VA: 0x75959211dc
	private Void _RenderChessLevel(Int32 level) { }
	// RVA: 0x3309388 VA: 0x7595921388
	private Void _SetSelectType(Int32 chessLevel) { }
	// RVA: 0x3309438 VA: 0x7595921438
	private Void _RenderCharCardInfo(Act1VAutoChessShopCharChessCardViewModel charChessCardViewModel) { }
	// RVA: 0x330a024 VA: 0x7595922024
	public Void OnCardClick() { }
	// RVA: 0x330a0c4 VA: 0x75959220c4
	public Void OnDiyCancelClick() { }
	// RVA: 0x330a164 VA: 0x7595922164
	public Void .ctor() { }
}
```