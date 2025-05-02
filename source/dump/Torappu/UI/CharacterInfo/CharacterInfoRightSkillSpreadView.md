# CharacterInfoRightSkillSpreadView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Single _currentHeight`

- `SimpleLayoutContent _skillContent`

- `GameObject _ableToSelect`

- `GameObject _alreadyIsSelect`

- `Text _skillDetail`

- `UISkillTagGroup _tagGroup`

- `Text _skillLevel`

- `GameObject _skillLevelPart`

- `GameObject _specMaxPart`

- `GameObject _maxPart`

- `GameObject _lvlupPart`

- `GameObject _trainPart`

- `GameObject _trainFullPart`

- `GameObject _noTrainPart`

- `Action refreshHeightAction`

- `UnityEvent _toTrainingRoom`

- `UnityEvent _toLvlup`

- `UnityEvent _toDetail`

- `UnityEvent _onChangeSkill`

- `UIStringEvent _onFocusSkill`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `String m_focusSkillId`

- `SkillGroupViewModel m_skillGroupViewModel`

- `TextGenerator m_textGenerate`


## Methods

- `Single GetAndRefreshHeight()`

- `Void _InitIfNot()`

- `Void Render(CharViewModel)`

- `SkillItemViewModel _CurrentSelectViewModel()`

- `Void _RenderSkill()`

- `Void OnToSkillLvlUp()`

- `Void OnToSkillDetail()`

- `Void OnToTrainingRoom()`

- `Void OnConfirmSkill()`

- `Void _OnFocusSkill(String)`

- `Void OnNoTrainingClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightSkillSpreadView : MonoBehaviour, IHotfixable
{
	private Single _currentHeight; // 0x18
	private SimpleLayoutContent _skillContent; // 0x20
	private GameObject _ableToSelect; // 0x28
	private GameObject _alreadyIsSelect; // 0x30
	private Text _skillDetail; // 0x38
	private UISkillTagGroup _tagGroup; // 0x40
	private Text _skillLevel; // 0x48
	private GameObject _skillLevelPart; // 0x50
	private GameObject _specMaxPart; // 0x58
	private GameObject _maxPart; // 0x60
	private GameObject _lvlupPart; // 0x68
	private GameObject _trainPart; // 0x70
	private GameObject _trainFullPart; // 0x78
	private GameObject _noTrainPart; // 0x80
	public Action refreshHeightAction; // 0x88
	private UnityEvent _toTrainingRoom; // 0x90
	private UnityEvent _toLvlup; // 0x98
	private UnityEvent _toDetail; // 0xa0
	private UnityEvent _onChangeSkill; // 0xa8
	private UIStringEvent _onFocusSkill; // 0xb0
	private Adapter m_adapter; // 0xb8
	private Boolean m_isInited; // 0xc0
	private String m_focusSkillId; // 0xc8
	private SkillGroupViewModel m_skillGroupViewModel; // 0xd0
	private TextGenerator m_textGenerate; // 0xd8
	private static DelegateBridge __Hotfix0_GetAndRefreshHeight; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__CurrentSelectViewModel; // 0x18
	private static DelegateBridge __Hotfix0__RenderSkill; // 0x20
	private static DelegateBridge __Hotfix0_OnToSkillLvlUp; // 0x28
	private static DelegateBridge __Hotfix0_OnToSkillDetail; // 0x30
	private static DelegateBridge __Hotfix0_OnToTrainingRoom; // 0x38
	private static DelegateBridge __Hotfix0_OnConfirmSkill; // 0x40
	private static DelegateBridge __Hotfix0__OnFocusSkill; // 0x48
	private static DelegateBridge __Hotfix0_OnNoTrainingClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2d84ab8 VA: 0x759539cab8
	public Single GetAndRefreshHeight() { }
	// RVA: 0x2d8775c VA: 0x759539f75c
	private Void _InitIfNot() { }
	// RVA: 0x2d848b4 VA: 0x759539c8b4
	public Void Render(CharViewModel viewModel) { }
	// RVA: 0x2d87ce4 VA: 0x759539fce4
	private SkillItemViewModel _CurrentSelectViewModel() { }
	// RVA: 0x2d878fc VA: 0x759539f8fc
	private Void _RenderSkill() { }
	// RVA: 0x2d87e0c VA: 0x759539fe0c
	public Void OnToSkillLvlUp() { }
	// RVA: 0x2d87e88 VA: 0x759539fe88
	public Void OnToSkillDetail() { }
	// RVA: 0x2d87f04 VA: 0x759539ff04
	public Void OnToTrainingRoom() { }
	// RVA: 0x2d87f80 VA: 0x759539ff80
	public Void OnConfirmSkill() { }
	// RVA: 0x2d87ffc VA: 0x759539fffc
	private Void _OnFocusSkill(String skillId) { }
	// RVA: 0x2d880a8 VA: 0x75953a00a8
	public Void OnNoTrainingClick() { }
	// RVA: 0x2d88144 VA: 0x75953a0144
	public Void .ctor() { }
}
```