# ClimbTowerSquadExpansionView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textCurrentStep`

- `Text _textTotalStep`

- `Text _textPos`

- `SimpleLayoutContent _slotList`

- `CanvasGroup _slotListCanvasGroup`

- `Single _animDelay`

- `UIAnimationLocation _btnConfirmAnim`

- `TwoStateToggle _btnStateToggle`

- `ClimbTowerBackgroundController _bkgController`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `ClimbTowerSquadExpansionModel m_expansionModel`

- `AnimationSwitchTween m_btnConfirmTween`


## Methods

- `Void set_onCharSelect(Action`3)`

- `IEnumerator PlaySpawnAnim()`

- `Void RegisterTutorialGo()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadExpansionView : DataBinder`1
{
	private Text _textCurrentStep; // 0x20
	private Text _textTotalStep; // 0x28
	private Text _textPos; // 0x30
	private SimpleLayoutContent _slotList; // 0x38
	private CanvasGroup _slotListCanvasGroup; // 0x40
	private Single _animDelay; // 0x48
	private UIAnimationLocation _btnConfirmAnim; // 0x50
	private TwoStateToggle _btnStateToggle; // 0x60
	private ClimbTowerBackgroundController _bkgController; // 0x68
	private Boolean m_hasInited; // 0x70
	private Adapter m_adapter; // 0x78
	private ClimbTowerSquadExpansionModel m_expansionModel; // 0x80
	private AnimationSwitchTween m_btnConfirmTween; // 0x88
	private List`1 m_slotItemViewList; // 0x90
	private Action`3 <onCharSelect>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_onCharSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onCharSelect; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_PlaySpawnAnim; // 0x18
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`3 onCharSelect { get; set; }

	// RVA: 0x2cd20d8 VA: 0x75952ea0d8
	private Action`3 get_onCharSelect() { }
	// RVA: 0x2cd04e8 VA: 0x75952e84e8
	public Void set_onCharSelect(Action`3 value) { }
	// RVA: 0x2cd2140 VA: 0x75952ea140
	public override Void OnValueChanged(ClimbTowerSquadExpansionProperty property) { }
	// RVA: 0x2cd14bc VA: 0x75952e94bc
	public IEnumerator PlaySpawnAnim() { }
	// RVA: 0x2cd194c VA: 0x75952e994c
	public Void RegisterTutorialGo() { }
	// RVA: 0x2cd2390 VA: 0x75952ea390
	private Void _InitIfNot() { }
	// RVA: 0x2cd26f8 VA: 0x75952ea6f8
	public Void .ctor() { }
}
```