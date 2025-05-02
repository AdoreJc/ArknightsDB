# BossRushStageChooseButtonView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `Text _textStageGroupName`

- `UIColorGraphic _buttonGraphic`

- `AnimationWrapper _animationWrapper`

- `TwoStateToggle _toggleBkg`

- `TwoStateToggle _toggleAllComplete`

- `TwoStateToggle _toggleCompleteFinal`

- `TwoStateToggle _toggleStageGroupUnlock`

- `SimpleLayoutContent _completeStageContent`

- `Text _textButtonNumber`

- `Text _textUnlockCond`

- `BossRushStageChooseItemModel m_cachedModel`

- `Adapter m_adapter`

- `Boolean m_hasInited`


## Properties

- `AnimationWrapper buttonAnim`


## Methods

- `AnimationWrapper get_buttonAnim()`

- `Void OnButtonClick()`

- `Void Init(Int32, Action`1)`

- `Void Render(BossRushStageChooseItemModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageChooseButtonView : MonoBehaviour, IHotfixable
{
	private Text _textStageGroupName; // 0x18
	private UIColorGraphic _buttonGraphic; // 0x20
	private AnimationWrapper _animationWrapper; // 0x28
	private TwoStateToggle _toggleBkg; // 0x30
	private TwoStateToggle _toggleAllComplete; // 0x38
	private TwoStateToggle _toggleCompleteFinal; // 0x40
	private TwoStateToggle _toggleStageGroupUnlock; // 0x48
	private StageChooseButtonIconConfig[] _iconConfigList; // 0x50
	private GameObject[] _bossIconList; // 0x58
	private SimpleLayoutContent _completeStageContent; // 0x60
	private Text _textButtonNumber; // 0x68
	private Text _textUnlockCond; // 0x70
	private BossRushStageChooseItemModel m_cachedModel; // 0x78
	private Adapter m_adapter; // 0x80
	private Boolean m_hasInited; // 0x88
	private Action`1 m_onStageGroupClicked; // 0x90
	private static DelegateBridge __Hotfix0_get_buttonAnim; // 0x0
	private static DelegateBridge __Hotfix0_OnButtonClick; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public AnimationWrapper buttonAnim { get; }

	// RVA: 0x2e6f280 VA: 0x7595487280
	public AnimationWrapper get_buttonAnim() { }
	// RVA: 0x2e6f378 VA: 0x7595487378
	public Void OnButtonClick() { }
	// RVA: 0x2e6f1a8 VA: 0x75954871a8
	public Void Init(Int32 cardNumber, Action`1 onStageGroupClicked) { }
	// RVA: 0x2e6ed10 VA: 0x7595486d10
	public Void Render(BossRushStageChooseItemModel itemModel) { }
	// RVA: 0x2e6f414 VA: 0x7595487414
	private Void _InitIfNot() { }
	// RVA: 0x2e6f710 VA: 0x7595487710
	public Void .ctor() { }
}
```