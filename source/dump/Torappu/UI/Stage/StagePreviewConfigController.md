# StagePreviewConfigController

**Namespace:** `Torappu.UI.Stage`


## Fields

- `TwoStateToggle _btnPractise`

- `TwoStateToggle _btnHard`

- `GameObject _btnHardLocked`

- `GameObject _btnSixStar`

- `TwoStateToggle _tglAutoBattle`

- `GameObject _autoBattleLocked`

- `GameObject _tglReplayStory`

- `GameObject _apProtect`

- `UIAnimationLocation _aniContinuousBtn`

- `Button _continuousBtn`

- `Text _textContinuousBattleTimes`

- `Text _apCostText`

- `Color _commonApCostColor`

- `Color _groupApCostColor`

- `Button _btnStartBattleAp`

- `RectTransform _containerStartBattleOverride`

- `StageStartBattleETButton _prefabStartBattleEt`

- `StageStartBattleCustomButton _prefabStartBattleEditablePredefined`

- `StageStartBattleETButton m_btnStartBattleEt`

- `StageStartBattleCustomButton m_btnStartBattleCustom`

- `AnimationSwitchTween m_aniContinuousBtnSwitchTween`

- `Boolean m_isInited`

- `Boolean m_isAutoBattleUnlocked`

- `Boolean m_isCampaign`

- `UIPageListener m_pageListener`


## Properties

- `UIPageListener pageListener`


## Methods

- `UIPageListener get_pageListener()`

- `Void OnAutoBattleLocked()`

- `Void _ShowPanelAsNormal(PreviewConfigViewModel)`

- `Void _ShowPanelAsHard(PreviewConfigViewModel)`

- `Void _ShowPanelAsSixStar(PreviewConfigViewModel)`

- `Void _UpdateStartBattleButton(PreviewConfigViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewConfigController : DataBinder`1
{
	private TwoStateToggle _btnPractise; // 0x20
	private TwoStateToggle _btnHard; // 0x28
	private GameObject _btnHardLocked; // 0x30
	private GameObject _btnSixStar; // 0x38
	private TwoStateToggle _tglAutoBattle; // 0x40
	private GameObject _autoBattleLocked; // 0x48
	private GameObject _tglReplayStory; // 0x50
	private GameObject _apProtect; // 0x58
	private UIAnimationLocation _aniContinuousBtn; // 0x60
	private Button _continuousBtn; // 0x70
	private Text _textContinuousBattleTimes; // 0x78
	protected Text _apCostText; // 0x80
	private Color _commonApCostColor; // 0x88
	private Color _groupApCostColor; // 0x98
	private Button _btnStartBattleAp; // 0xa8
	private RectTransform _containerStartBattleOverride; // 0xb0
	private StageStartBattleETButton _prefabStartBattleEt; // 0xb8
	private StageStartBattleCustomButton _prefabStartBattleEditablePredefined; // 0xc0
	private StageStartBattleETButton m_btnStartBattleEt; // 0xc8
	private StageStartBattleCustomButton m_btnStartBattleCustom; // 0xd0
	private AnimationSwitchTween m_aniContinuousBtnSwitchTween; // 0xd8
	private Boolean m_isInited; // 0xe0
	private Boolean m_isAutoBattleUnlocked; // 0xe1
	private Boolean m_isCampaign; // 0xe2
	private UIPageListener m_pageListener; // 0xe8
	private static DelegateBridge __Hotfix0_get_pageListener; // 0x0
	private static DelegateBridge __Hotfix0_OnAutoBattleLocked; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__ShowPanelAsNormal; // 0x18
	private static DelegateBridge __Hotfix0__ShowPanelAsHard; // 0x20
	private static DelegateBridge __Hotfix0__ShowPanelAsSixStar; // 0x28
	private static DelegateBridge __Hotfix0__UpdateStartBattleButton; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected UIPageListener pageListener { get; }

	// RVA: 0x2fa7a48 VA: 0x75955bfa48
	protected UIPageListener get_pageListener() { }
	// RVA: 0x2fa7b10 VA: 0x75955bfb10
	public Void OnAutoBattleLocked() { }
	// RVA: 0x2fa7bb8 VA: 0x75955bfbb8
	public override Void OnValueChanged(PreviewConfigViewProperty property) { }
	// RVA: 0x2fa841c VA: 0x75955c041c
	private Void _ShowPanelAsNormal(PreviewConfigViewModel viewModel) { }
	// RVA: 0x2fa85bc VA: 0x75955c05bc
	private Void _ShowPanelAsHard(PreviewConfigViewModel viewModel) { }
	// RVA: 0x2fa86b0 VA: 0x75955c06b0
	private Void _ShowPanelAsSixStar(PreviewConfigViewModel viewModel) { }
	// RVA: 0x2fa8118 VA: 0x75955c0118
	private Void _UpdateStartBattleButton(PreviewConfigViewModel viewModel) { }
	// RVA: 0x2fa8008 VA: 0x75955c0008
	private Void _InitIfNot() { }
	// RVA: 0x2fa8c74 VA: 0x75955c0c74
	public Void .ctor() { }
}
```