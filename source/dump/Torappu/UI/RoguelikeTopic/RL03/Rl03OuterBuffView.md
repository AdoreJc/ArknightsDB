# Rl03OuterBuffView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Rl03OuterBuffContentView _contentView`

- `Rl03OuterBuffBottomView _bottomView`

- `UIAnimationLocation _enterAnim`

- `Single _upgradeAnimDelay`

- `UIAnimationLocation _selectAnim`

- `ScrollRect _scroll`

- `RectTransform _contentRect`

- `RectTransform _locationRect`

- `GameObject _btnLeft`

- `GameObject _btnRight`

- `Single _focusLocation`

- `Single _focusDuration`

- `Text _tokenName`

- `Text _tokenCount`

- `Text _activeCount`

- `Text _totalCount`

- `GameObject _panelTokenAll`

- `GameObject _panelToken`

- `CanvasGroup _leftCanvasGroup`

- `CanvasGroup _rightCanvasGroup`

- `Action onSummaryClick`

- `Boolean m_isInited`

- `UIPage m_page`

- `Int32 m_cachedDiffCount`

- `Rl03OuterBuffViewModel m_cachedViewModel`

- `AnimationSwitchTween m_selectSwitchTween`

- `LocationHandler m_locationHandler`

- `Tween m_totemTween`

- `Tween m_enterTween`


## Methods

- `Void Update()`

- `Void Init(Rl03OuterBuffViewModel)`

- `Void _InitIfNot()`

- `Void _PlayEnterAnim()`

- `Void _PlayTotemAnim()`

- `Void _PlayUpgradeAnim(Int32)`

- `Void _InitLocationGroup(Rl03OuterBuffViewModel)`

- `Void OnLeftFocus()`

- `Void OnRightFocus()`

- `Void OnBackgroudPress()`

- `Void OnSummaryClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffView : DataBinder`1
{
	private Rl03OuterBuffContentView _contentView; // 0x20
	private Rl03OuterBuffBottomView _bottomView; // 0x28
	private UIAnimationLocation _enterAnim; // 0x30
	private List`1 _enterAnims; // 0x40
	private Single _upgradeAnimDelay; // 0x48
	private List`1 _upgradeAnims; // 0x50
	private UIAnimationLocation _selectAnim; // 0x58
	private ScrollRect _scroll; // 0x68
	private RectTransform _contentRect; // 0x70
	private RectTransform _locationRect; // 0x78
	private List`1 _locationGroups; // 0x80
	private GameObject _btnLeft; // 0x88
	private GameObject _btnRight; // 0x90
	private Single _focusLocation; // 0x98
	private Single _focusDuration; // 0x9c
	private Text _tokenName; // 0xa0
	private Text _tokenCount; // 0xa8
	private Text _activeCount; // 0xb0
	private Text _totalCount; // 0xb8
	private GameObject _panelTokenAll; // 0xc0
	private GameObject _panelToken; // 0xc8
	private CanvasGroup _leftCanvasGroup; // 0xd0
	private CanvasGroup _rightCanvasGroup; // 0xd8
	public Action`1 onNodeClick; // 0xe0
	public Action`1 onUpgradeClick; // 0xe8
	public Action onSummaryClick; // 0xf0
	private Boolean m_isInited; // 0xf8
	private UIPage m_page; // 0x100
	private Int32 m_cachedDiffCount; // 0x108
	private Rl03OuterBuffViewModel m_cachedViewModel; // 0x110
	private AnimationSwitchTween m_selectSwitchTween; // 0x118
	private List`1 m_locationDatas; // 0x120
	private LocationHandler m_locationHandler; // 0x128
	private Tween m_totemTween; // 0x130
	private Tween m_enterTween; // 0x138
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x20
	private static DelegateBridge __Hotfix0__PlayTotemAnim; // 0x28
	private static DelegateBridge __Hotfix0__PlayUpgradeAnim; // 0x30
	private static DelegateBridge __Hotfix0__InitLocationGroup; // 0x38
	private static DelegateBridge __Hotfix0_OnLeftFocus; // 0x40
	private static DelegateBridge __Hotfix0_OnRightFocus; // 0x48
	private static DelegateBridge __Hotfix0_OnBackgroudPress; // 0x50
	private static DelegateBridge __Hotfix0_OnSummaryClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x26afd70 VA: 0x7594cc7d70
	private Void Update() { }
	// RVA: 0x26a8970 VA: 0x7594cc0970
	public Void Init(Rl03OuterBuffViewModel viewModel) { }
	// RVA: 0x26b0580 VA: 0x7594cc8580
	public override Void OnValueChanged(Rl03OuterBuffProperty property) { }
	// RVA: 0x26afe58 VA: 0x7594cc7e58
	private Void _InitIfNot() { }
	// RVA: 0x26b0438 VA: 0x7594cc8438
	private Void _PlayEnterAnim() { }
	// RVA: 0x26b02d4 VA: 0x7594cc82d4
	private Void _PlayTotemAnim() { }
	// RVA: 0x26b098c VA: 0x7594cc898c
	private Void _PlayUpgradeAnim(Int32 activeDiffCount) { }
	// RVA: 0x26affd8 VA: 0x7594cc7fd8
	private Void _InitLocationGroup(Rl03OuterBuffViewModel viewModel) { }
	// RVA: 0x26b0e4c VA: 0x7594cc8e4c
	public Void OnLeftFocus() { }
	// RVA: 0x26b0f40 VA: 0x7594cc8f40
	public Void OnRightFocus() { }
	// RVA: 0x26b1034 VA: 0x7594cc9034
	public Void OnBackgroudPress() { }
	// RVA: 0x26b10bc VA: 0x7594cc90bc
	public Void OnSummaryClick() { }
	// RVA: 0x26b1140 VA: 0x7594cc9140
	public Void .ctor() { }
}
```