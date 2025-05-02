# CharacterInfoRightSkillHideView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `SimpleLayoutContent _skillContent`

- `Text _skillLevel`

- `GameObject _levelUpPart`

- `GameObject _trainingPart`

- `GameObject _maxPart`

- `GameObject _noSkillPart`

- `UnityEvent _onSkillClick`

- `Adapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(CharViewModel)`

- `Void OnSkillClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightSkillHideView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _skillContent; // 0x18
	private Text _skillLevel; // 0x20
	private GameObject _levelUpPart; // 0x28
	private GameObject _trainingPart; // 0x30
	private GameObject _maxPart; // 0x38
	private GameObject _noSkillPart; // 0x40
	private UnityEvent _onSkillClick; // 0x48
	private Adapter m_adapter; // 0x50
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnSkillClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d86e70 VA: 0x759539ee70
	private Void _InitIfNot() { }
	// RVA: 0x2d846a8 VA: 0x759539c6a8
	public Void Render(CharViewModel viewModel) { }
	// RVA: 0x2d86fac VA: 0x759539efac
	public Void OnSkillClick() { }
	// RVA: 0x2d87028 VA: 0x759539f028
	public Void .ctor() { }
}
```