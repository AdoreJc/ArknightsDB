# RoguelikeCommonOuterBuffView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeCommonOuterBuffContentView _contentView`

- `RoguelikeCommonOuterBuffBottomView _bottomView`

- `UIAnimationLocation _enterAnim`

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

- `RoguelikeCommonOuterBuffViewModel m_cachedViewModel`

- `AnimationSwitchTween m_selectSwitchTween`

- `LocationHandler m_locationHandler`

- `Tween m_enterTween`


## Methods

- `Void Update()`

- `Void Init(RoguelikeCommonOuterBuffViewModel)`

- `Void _InitIfNot()`

- `Void _PlayEnterAnim()`

- `Void _InitLocationGroup(RoguelikeCommonOuterBuffViewModel)`

- `Void OnLeftFocus()`

- `Void OnRightFocus()`

- `Void OnBackgroundPress()`

- `Void OnSummaryClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffView : DataBinder`1
{
	private RoguelikeCommonOuterBuffContentView _contentView; // 0x20
	private RoguelikeCommonOuterBuffBottomView _bottomView; // 0x28
	private UIAnimationLocation _enterAnim; // 0x30
	private UIAnimationLocation _selectAnim; // 0x40
	private ScrollRect _scroll; // 0x50
	private RectTransform _contentRect; // 0x58
	private RectTransform _locationRect; // 0x60
	private List`1 _locationGroups; // 0x68
	private GameObject _btnLeft; // 0x70
	private GameObject _btnRight; // 0x78
	private Single _focusLocation; // 0x80
	private Single _focusDuration; // 0x84
	private Text _tokenName; // 0x88
	private Text _tokenCount; // 0x90
	private Text _activeCount; // 0x98
	private Text _totalCount; // 0xa0
	private GameObject _panelTokenAll; // 0xa8
	private GameObject _panelToken; // 0xb0
	private CanvasGroup _leftCanvasGroup; // 0xb8
	private CanvasGroup _rightCanvasGroup; // 0xc0
	public Action`1 onNodeClick; // 0xc8
	public Action`1 onUpgradeClick; // 0xd0
	public Action onSummaryClick; // 0xd8
	private Boolean m_isInited; // 0xe0
	private RoguelikeCommonOuterBuffViewModel m_cachedViewModel; // 0xe8
	private AnimationSwitchTween m_selectSwitchTween; // 0xf0
	private List`1 m_locationDatas; // 0xf8
	private LocationHandler m_locationHandler; // 0x100
	private Tween m_enterTween; // 0x108
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x20
	private static DelegateBridge __Hotfix0__InitLocationGroup; // 0x28
	private static DelegateBridge __Hotfix0_OnLeftFocus; // 0x30
	private static DelegateBridge __Hotfix0_OnRightFocus; // 0x38
	private static DelegateBridge __Hotfix0_OnBackgroundPress; // 0x40
	private static DelegateBridge __Hotfix0_OnSummaryClick; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2666664 VA: 0x7594c7e664
	private Void Update() { }
	// RVA: 0x265ef64 VA: 0x7594c76f64
	public Void Init(RoguelikeCommonOuterBuffViewModel viewModel) { }
	// RVA: 0x2666ca8 VA: 0x7594c7eca8
	public override Void OnValueChanged(RoguelikeCommonOuterBuffProperty property) { }
	// RVA: 0x266674c VA: 0x7594c7e74c
	private Void _InitIfNot() { }
	// RVA: 0x2666b60 VA: 0x7594c7eb60
	private Void _PlayEnterAnim() { }
	// RVA: 0x2666864 VA: 0x7594c7e864
	private Void _InitLocationGroup(RoguelikeCommonOuterBuffViewModel viewModel) { }
	// RVA: 0x26673c8 VA: 0x7594c7f3c8
	public Void OnLeftFocus() { }
	// RVA: 0x26674bc VA: 0x7594c7f4bc
	public Void OnRightFocus() { }
	// RVA: 0x26675b0 VA: 0x7594c7f5b0
	public Void OnBackgroundPress() { }
	// RVA: 0x2667638 VA: 0x7594c7f638
	public Void OnSummaryClick() { }
	// RVA: 0x26676bc VA: 0x7594c7f6bc
	public Void .ctor() { }
}
```