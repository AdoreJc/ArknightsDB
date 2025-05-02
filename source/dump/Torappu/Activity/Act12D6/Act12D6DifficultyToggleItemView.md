# Act12D6DifficultyToggleItemView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Text _textDifficulty`

- `Text _textDesc`

- `GameObject _panelDesc`

- `Animator _animator`

- `GameObject _imageLocked`

- `UIStringEvent OnLockedToggleClicked`

- `String m_cachedModeName`

- `String <difficultyId>k__BackingField`


## Properties

- `String difficultyId`


## Methods

- `String get_difficultyId()`

- `Void set_difficultyId(String)`

- `Void OnClick()`

- `Void Render(RoguelikeModeData, Boolean)`

- `Void SwitchOnState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6DifficultyToggleItemView : MonoBehaviour, IHotfixable
{
	private Text _textDifficulty; // 0x18
	private Text _textDesc; // 0x20
	private GameObject _panelDesc; // 0x28
	private Animator _animator; // 0x30
	private GameObject _imageLocked; // 0x38
	public UIStringEvent OnLockedToggleClicked; // 0x40
	private String m_cachedModeName; // 0x48
	private String <difficultyId>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_difficultyId; // 0x0
	private static DelegateBridge __Hotfix0_set_difficultyId; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_SwitchOnState; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String difficultyId { get; set; }

	// RVA: 0x3472904 VA: 0x7595a8a904
	public String get_difficultyId() { }
	// RVA: 0x347296c VA: 0x7595a8a96c
	public Void set_difficultyId(String value) { }
	// RVA: 0x34729f0 VA: 0x7595a8a9f0
	public Void OnClick() { }
	// RVA: 0x3472a84 VA: 0x7595a8aa84
	public Void Render(RoguelikeModeData modeData, Boolean locked) { }
	// RVA: 0x3472c10 VA: 0x7595a8ac10
	public Void SwitchOnState(Boolean isOn) { }
	// RVA: 0x3472d70 VA: 0x7595a8ad70
	public Void .ctor() { }
}
```