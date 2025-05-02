# MainlineDiffGroupRewardView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `SimpleLayoutContent _content`

- `TwoStateToggle _showNextTimeToggle`

- `GameObject _buttonContainer`

- `Text _allApCost`

- `RectTransform _selectPart`

- `Text _detailText`

- `UIStringEvent _onStageRewardClick`

- `Boolean m_cacheAutoSelect`

- `Boolean m_isInited`

- `Adatper m_adapter`


## Properties

- `Boolean cacheAutoSelect`


## Methods

- `Boolean get_cacheAutoSelect()`

- `Void _InitIfNot()`

- `Void Render(StageViewModel, Boolean)`

- `Void ChangeClickNotShow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class MainlineDiffGroupRewardView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private TwoStateToggle _showNextTimeToggle; // 0x20
	private GameObject _buttonContainer; // 0x28
	private Text _allApCost; // 0x30
	private RectTransform _selectPart; // 0x38
	private Text _detailText; // 0x40
	private UIStringEvent _onStageRewardClick; // 0x48
	private Boolean m_cacheAutoSelect; // 0x50
	private Boolean m_isInited; // 0x51
	private Adatper m_adapter; // 0x58
	private static DelegateBridge __Hotfix0_get_cacheAutoSelect; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_ChangeClickNotShow; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean cacheAutoSelect { get; }

	// RVA: 0x2ef435c VA: 0x759550c35c
	public Boolean get_cacheAutoSelect() { }
	// RVA: 0x2ef4cb8 VA: 0x759550ccb8
	private Void _InitIfNot() { }
	// RVA: 0x2ef3e30 VA: 0x759550be30
	public Void Render(StageViewModel stageViewModel, Boolean isToSquad) { }
	// RVA: 0x2ef4e0c VA: 0x759550ce0c
	public Void ChangeClickNotShow() { }
	// RVA: 0x2ef4e8c VA: 0x759550ce8c
	public Void .ctor() { }
}
```