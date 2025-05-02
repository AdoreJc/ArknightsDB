# HandBookInfoStageSkillItemView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `GameObject _unlockPartGo`

- `GameObject _emptyPartGo`

- `Text _textName`

- `Image _imageIcon`

- `Image _specialLevelIcon`

- `GameObject _spInitGo`

- `Text _textSpInit`

- `GameObject _spCostGo`

- `Text _textSpCost`

- `UISkillTagGroup _skillTagGroup`

- `Text _textDesc`

- `UIAnimationLocation _selectAnim`

- `Boolean m_isInited`

- `Int32 m_cachedIndex`

- `Boolean m_cachedSelected`

- `AnimationSwitchTween m_switchTween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(SkillItemViewModel, Int32, Boolean)`

- `Void OnSelectSkill()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoStageSkillItemView : MonoBehaviour, IHotfixable
{
	private GameObject _unlockPartGo; // 0x18
	private GameObject _emptyPartGo; // 0x20
	private Text _textName; // 0x28
	private Image _imageIcon; // 0x30
	private Image _specialLevelIcon; // 0x38
	private GameObject _spInitGo; // 0x40
	private Text _textSpInit; // 0x48
	private GameObject _spCostGo; // 0x50
	private Text _textSpCost; // 0x58
	private UISkillTagGroup _skillTagGroup; // 0x60
	private Text _textDesc; // 0x68
	private UIAnimationLocation _selectAnim; // 0x70
	private Sprite[] _levelIconList; // 0x80
	private Boolean m_isInited; // 0x88
	private Int32 m_cachedIndex; // 0x8c
	private Boolean m_cachedSelected; // 0x90
	private AnimationSwitchTween m_switchTween; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnSelectSkill; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2eadf48 VA: 0x75954c5f48
	public Void Render(SkillItemViewModel skillData, Int32 idx, Boolean isSelect) { }
	// RVA: 0x2eae2fc VA: 0x75954c62fc
	public Void OnSelectSkill() { }
	// RVA: 0x2eae20c VA: 0x75954c620c
	private Void _InitIfNot() { }
	// RVA: 0x2eae3ec VA: 0x75954c63ec
	public Void .ctor() { }
}
```