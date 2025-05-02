# CharacterShowBranchView

**Namespace:** `Torappu.UI.CharacterShow`


## Fields

- `Image _imgSubProf`

- `Text _textSubProf`

- `Text _textTraitDesc`

- `LayoutElement _layoutTraitDesc`

- `SimpleLayoutContent _equipList`

- `SimpleLayoutContent _talentList`

- `GameObject _unlockHintGo`

- `Text _textUnlockHint`

- `GameObject _equipListGo`

- `GameObject _emptyEquipGo`

- `GameObject _emptyTalentGo`

- `Text _selectEquipName`

- `RectTransform _equipContentRectTransform`

- `UIWrappedScrollRect _equipScroll`

- `Single _limitEquipCntScrollWidth`

- `Single _maxEquipCntScrollWidth`

- `GameObject _singleEquipGo`

- `CharacterShowEquipItem _singleEquipItem`

- `Boolean m_hasInited`

- `CharacterShowV2Model m_charShowModel`

- `EquipListAdapter m_equipListAdapter`

- `TalentListAdapter m_talentListAdapter`

- `TextGenerator m_textGenerator`

- `Int32 m_refreshSeqNum`


## Properties

- `UIWrappedScrollRect equipScroll`


## Methods

- `UIWrappedScrollRect get_equipScroll()`

- `Void _UpdateEquipView()`

- `Void _InitIfNot()`

- `Single _GetTraitMaxHeight()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowBranchView : CharacterShowRightInfoViewBase
{
	private Image _imgSubProf; // 0x20
	private Text _textSubProf; // 0x28
	private Text _textTraitDesc; // 0x30
	private LayoutElement _layoutTraitDesc; // 0x38
	private SimpleLayoutContent _equipList; // 0x40
	private SimpleLayoutContent _talentList; // 0x48
	private GameObject _unlockHintGo; // 0x50
	private Text _textUnlockHint; // 0x58
	private GameObject _equipListGo; // 0x60
	private GameObject _emptyEquipGo; // 0x68
	private GameObject _emptyTalentGo; // 0x70
	private Text _selectEquipName; // 0x78
	private RectTransform _equipContentRectTransform; // 0x80
	private UIWrappedScrollRect _equipScroll; // 0x88
	private Single _limitEquipCntScrollWidth; // 0x90
	private Single _maxEquipCntScrollWidth; // 0x94
	private GameObject _singleEquipGo; // 0x98
	private CharacterShowEquipItem _singleEquipItem; // 0xa0
	private Boolean m_hasInited; // 0xa8
	private CharacterShowV2Model m_charShowModel; // 0xb0
	private EquipListAdapter m_equipListAdapter; // 0xb8
	private TalentListAdapter m_talentListAdapter; // 0xc0
	private TextGenerator m_textGenerator; // 0xc8
	private Int32 m_refreshSeqNum; // 0xd0
	private static DelegateBridge __Hotfix0_get_equipScroll; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__UpdateEquipView; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__GetTraitMaxHeight; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public UIWrappedScrollRect equipScroll { get; }

	// RVA: 0x2ce08e0 VA: 0x75952f88e0
	public UIWrappedScrollRect get_equipScroll() { }
	// RVA: 0x2ce5070 VA: 0x75952fd070
	public override Void OnValueChanged(CharacterShowProp property) { }
	// RVA: 0x2ce5390 VA: 0x75952fd390
	private Void _UpdateEquipView() { }
	// RVA: 0x2ce5248 VA: 0x75952fd248
	private Void _InitIfNot() { }
	// RVA: 0x2ce5b90 VA: 0x75952fdb90
	private Single _GetTraitMaxHeight() { }
	// RVA: 0x2ce5d08 VA: 0x75952fdd08
	public Void .ctor() { }
}
```