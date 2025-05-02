# CharacterShowSkillGroupView

**Namespace:** `Torappu.UI.CharacterShow`


## Fields

- `UICommentedText _textDesc`

- `LayoutElement _layoutDesc`

- `UISkillTagGroup _tagGroup`

- `SimpleLayoutContent _skillList`

- `GameObject _skillGroupGo`

- `GameObject _emptyGo`

- `GameObject _unlockCondGo`

- `Text _textUnlockHint`

- `UIAtlasImage _imgUnlockIcon`

- `UIAtlasObject _atlasUnlockIcon`

- `String _iconEvolveOneUnlockName`

- `String _iconEvolveTwoUnlockName`

- `GameObject _singleSkillGo`

- `CharacterShowSkillItem _singleSkillItem`

- `Boolean m_hasInited`

- `CharacterShowV2Model m_charShowModel`

- `SkillListAdapter m_skillListAdapter`

- `TextGenerator m_textGenerator`


## Methods

- `Void _RenderSkillView()`

- `Void _UpdateSelectedSkillInfo()`

- `String _GetUnlockIconName(UnlockCondition)`

- `Void _InitIfNot()`

- `Single _GetSkillDescMaxHeight()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowSkillGroupView : CharacterShowRightInfoViewBase
{
	private UICommentedText _textDesc; // 0x20
	private LayoutElement _layoutDesc; // 0x28
	private UISkillTagGroup _tagGroup; // 0x30
	private SimpleLayoutContent _skillList; // 0x38
	private GameObject _skillGroupGo; // 0x40
	private GameObject _emptyGo; // 0x48
	private GameObject _unlockCondGo; // 0x50
	private Text _textUnlockHint; // 0x58
	private UIAtlasImage _imgUnlockIcon; // 0x60
	private UIAtlasObject _atlasUnlockIcon; // 0x68
	private String _iconEvolveOneUnlockName; // 0x70
	private String _iconEvolveTwoUnlockName; // 0x78
	private GameObject _singleSkillGo; // 0x80
	private CharacterShowSkillItem _singleSkillItem; // 0x88
	private Boolean m_hasInited; // 0x90
	private CharacterShowV2Model m_charShowModel; // 0x98
	private SkillListAdapter m_skillListAdapter; // 0xa0
	private TextGenerator m_textGenerator; // 0xa8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderSkillView; // 0x8
	private static DelegateBridge __Hotfix0__UpdateSelectedSkillInfo; // 0x10
	private static DelegateBridge __Hotfix0__GetUnlockIconName; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__GetSkillDescMaxHeight; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2ce6db4 VA: 0x75952fedb4
	public override Void OnValueChanged(CharacterShowProp property) { }
	// RVA: 0x2ce6f70 VA: 0x75952fef70
	private Void _RenderSkillView() { }
	// RVA: 0x2ce70e8 VA: 0x75952ff0e8
	private Void _UpdateSelectedSkillInfo() { }
	// RVA: 0x2ce76dc VA: 0x75952ff6dc
	private String _GetUnlockIconName(UnlockCondition unlockCond) { }
	// RVA: 0x2ce6e78 VA: 0x75952fee78
	private Void _InitIfNot() { }
	// RVA: 0x2ce780c VA: 0x75952ff80c
	private Single _GetSkillDescMaxHeight() { }
	// RVA: 0x2ce7940 VA: 0x75952ff940
	public Void .ctor() { }
}
```