# BossRushRelicNodeView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `GameObject _objUpgradePart`

- `GameObject _objMaxPart`

- `GameObject _objUpBg`

- `GameObject _objLackBg`

- `Slider _sliderLevelProgress`

- `Button _btnUpgrade`

- `Image _imgRelicIcon`

- `Text _txtName`

- `Text _txtLockName`

- `Text _txtLevel`

- `Text _txtDes`

- `Text _txtDesLock`

- `UICommonTrackPoint _relicTrackPoint`

- `UIAnimationLocation _selectAnim`

- `UIAnimationLocation _enterAnim`

- `BossRushRelicNodeModel m_relicNodeModel`

- `Boolean m_hasInited`

- `String m_actId`

- `AnimationSwitchTween m_relicSelectSwitchTween`

- `TrackPointViewProperty m_trackPointProp`

- `Single m_selectTweenDuration`

- `Tween m_enterTween`

- `Int32 m_cachedEnterAnimTick`


## Methods

- `Void set_onUpgradeClicked(Action`1)`

- `Void set_onRelicClicked(Action`1)`

- `Void Render(String, BossRushRelicNodeModel, Action`1, Action`1, Int32, Int32)`

- `Void RenderSelect(BossRushRelicNodeModel)`

- `Void _InitIfNot(String, Action`1, Action`1)`

- `Void EventOnUpgradeClicked()`

- `Void EventOnRelicClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushRelicNodeView : MonoBehaviour, IHotfixable
{
	private const Single ENTER_ANIM_DELAY; // 0x0
	private GameObject _objUpgradePart; // 0x18
	private GameObject _objMaxPart; // 0x20
	private GameObject _objUpBg; // 0x28
	private GameObject _objLackBg; // 0x30
	private Slider _sliderLevelProgress; // 0x38
	private Button _btnUpgrade; // 0x40
	private GameObject[] _unLockState; // 0x48
	private GameObject[] _lockState; // 0x50
	private Image _imgRelicIcon; // 0x58
	private Text _txtName; // 0x60
	private Text _txtLockName; // 0x68
	private Text _txtLevel; // 0x70
	private Text _txtDes; // 0x78
	private Text _txtDesLock; // 0x80
	private UICommonTrackPoint _relicTrackPoint; // 0x88
	private UIAnimationLocation _selectAnim; // 0x90
	private UIAnimationLocation _enterAnim; // 0xa0
	private Action`1 <onUpgradeClicked>k__BackingField; // 0xb0
	private Action`1 <onRelicClicked>k__BackingField; // 0xb8
	private BossRushRelicNodeModel m_relicNodeModel; // 0xc0
	private Boolean m_hasInited; // 0xc8
	private String m_actId; // 0xd0
	private AnimationSwitchTween m_relicSelectSwitchTween; // 0xd8
	private TrackPointViewProperty m_trackPointProp; // 0xe0
	private Single m_selectTweenDuration; // 0xe8
	private Tween m_enterTween; // 0xf0
	private Int32 m_cachedEnterAnimTick; // 0xf8
	private static DelegateBridge __Hotfix0_get_onUpgradeClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onUpgradeClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onRelicClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onRelicClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_RenderSelect; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_EventOnUpgradeClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnRelicClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`1 onUpgradeClicked { get; set; }
	private Action`1 onRelicClicked { get; set; }

	// RVA: 0x2e5af2c VA: 0x7595472f2c
	private Action`1 get_onUpgradeClicked() { }
	// RVA: 0x2e5af94 VA: 0x7595472f94
	public Void set_onUpgradeClicked(Action`1 value) { }
	// RVA: 0x2e5b018 VA: 0x7595473018
	private Action`1 get_onRelicClicked() { }
	// RVA: 0x2e5b080 VA: 0x7595473080
	public Void set_onRelicClicked(Action`1 value) { }
	// RVA: 0x2e5b104 VA: 0x7595473104
	public Void Render(String aId, BossRushRelicNodeModel model, Action`1 upgrade, Action`1 select, Int32 tickNum, Int32 position) { }
	// RVA: 0x2e5b76c VA: 0x759547376c
	public Void RenderSelect(BossRushRelicNodeModel model) { }
	// RVA: 0x2e5b4b0 VA: 0x75954734b0
	private Void _InitIfNot(String aId, Action`1 upgrade, Action`1 select) { }
	// RVA: 0x2e5b904 VA: 0x7595473904
	public Void EventOnUpgradeClicked() { }
	// RVA: 0x2e5b9a4 VA: 0x75954739a4
	public Void EventOnRelicClick() { }
	// RVA: 0x2e5ba54 VA: 0x7595473a54
	public Void .ctor() { }
}
```