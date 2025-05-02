# CharacterSkillLvlUpGroupView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Animator _animator`

- `Boolean up`

- `Image _skillLvlBack`

- `Image _skillLvl20`

- `Image _skillLvl80`

- `Boolean m_isTrasiting`

- `Boolean m_cachedDownFlag`

- `Boolean m_inited`


## Methods

- `Void ChangeState(Boolean)`

- `Void SetAsFirstSibling()`

- `Void SetAsLastSibling()`

- `Void _InitIfNot()`

- `Boolean _TrySwitchAnimator(Boolean)`

- `Void _RenderSkillViewCommentText(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterSkillLvlUpGroupView : DataBinder`1
{
	private Animator _animator; // 0x20
	private Boolean up; // 0x28
	private CharacterInfoSkillView[] _skillViews; // 0x30
	private Image _skillLvlBack; // 0x38
	private Image _skillLvl20; // 0x40
	private Image _skillLvl80; // 0x48
	private Image[] _skillLvlBackAlpha; // 0x50
	private Boolean m_isTrasiting; // 0x58
	private Boolean m_cachedDownFlag; // 0x59
	private Boolean m_inited; // 0x5a
	private static DelegateBridge __Hotfix0_ChangeState; // 0x0
	private static DelegateBridge __Hotfix0_SetAsFirstSibling; // 0x8
	private static DelegateBridge __Hotfix0_SetAsLastSibling; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__TrySwitchAnimator; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0__RenderSkillViewCommentText; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2d8a80c VA: 0x75953a280c
	public Void ChangeState(Boolean upFlag) { }
	// RVA: 0x2d8aa98 VA: 0x75953a2a98
	public Void SetAsFirstSibling() { }
	// RVA: 0x2d8ab14 VA: 0x75953a2b14
	public Void SetAsLastSibling() { }
	// RVA: 0x2d8ab90 VA: 0x75953a2b90
	private Void _InitIfNot() { }
	// RVA: 0x2d8a8b4 VA: 0x75953a28b4
	private Boolean _TrySwitchAnimator(Boolean upFlag) { }
	// RVA: 0x2d8ac18 VA: 0x75953a2c18
	public override Void OnValueChanged(SkillGroupViewProperty property) { }
	// RVA: 0x2d8a9cc VA: 0x75953a29cc
	private Void _RenderSkillViewCommentText(Boolean isDownState) { }
	// RVA: 0x2d8af04 VA: 0x75953a2f04
	public Void .ctor() { }
}
```