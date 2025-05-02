# CharacterInfoSelectSkillGroup

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `UIIntEvent _eventSkillToggleClick`

- `Image _skillLevelSolid`

- `Image _skillLevelImage`

- `GameObject _pageLvlUpBtn`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnSkillToggleClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSelectSkillGroup : DataBinder`1
{
	private CharacterInfoSelectSkillView[] _skillViews; // 0x20
	private UIIntEvent _eventSkillToggleClick; // 0x28
	private Image _skillLevelSolid; // 0x30
	private Image _skillLevelImage; // 0x38
	private GameObject _pageLvlUpBtn; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnSkillToggleClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d88420 VA: 0x75953a0420
	private Void _InitIfNot() { }
	// RVA: 0x2d88544 VA: 0x75953a0544
	public override Void OnValueChanged(SkillGroupViewProperty property) { }
	// RVA: 0x2d88774 VA: 0x75953a0774
	private Void _OnSkillToggleClick(Int32 skillIndex) { }
	// RVA: 0x2d88820 VA: 0x75953a0820
	public Void .ctor() { }
}
```