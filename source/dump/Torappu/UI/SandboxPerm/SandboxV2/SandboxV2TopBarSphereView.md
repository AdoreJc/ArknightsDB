# SandboxV2TopBarSphereView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _ringNormal`

- `GameObject _ringRift`

- `GameObject _ringChallenge`

- `GameObject _panelNormal`

- `GameObject _panelRift`

- `GameObject _panelChallenge`

- `RectTransform _dayAngle`

- `GameObject _panelSettleDay`

- `GameObject _panelNormalDay`

- `CanvasGroup _panelCrossDay`

- `CanvasGroup _panelDownContent`

- `GameObject _normalCrossDay`

- `GameObject _normalRiftCrossDay`

- `GameObject _riftSettleCrossDay`

- `GameObject _panelRiftReserved`

- `GameObject _panelRiftQuestSucc`

- `GameObject _panelRiftQuestFail`

- `Text _day`

- `Text _maxDay`

- `SimpleLayoutContent _decisionContent`

- `UIBlendRTImage _bkgBlur`

- `UIAnimationLocation _switchAnim`

- `GameObject _panelNormalBkg`

- `GameObject _panelEmergencyBkg`

- `Color _normalTextIconColor`

- `Color _emergencyTextIconColor`

- `Button _buttonSphereCrossDay`

- `Button _buttonSphereNormal`

- `Text _textDaySurvive`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `UIPageFinder m_pageFinder`

- `FadeTween m_crossDayTween`

- `SandboxV2DungeonViewModel m_cachedViewModel`

- `Action onContentClick`


## Methods

- `Void Render(SandboxV2DungeonViewModel)`

- `Void _RenderRing(Mode, Single)`

- `Void _RenderTip(Mode, Boolean, Boolean, Boolean)`

- `Void _RenderCrossDay(Mode, Boolean, Boolean, Boolean, Boolean, Boolean)`

- `Void _InitIfNot()`

- `Void OnBtnGameflowPanelClicked()`

- `Void OnSphereContentClick()`

- `GameObject TutorialOnly_GetCrossDayBtnGo()`

- `GameObject TutorialOnly_GetSphereBtnGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2TopBarSphereView : MonoBehaviour, IHotfixable
{
	private GameObject _ringNormal; // 0x18
	private GameObject _ringRift; // 0x20
	private GameObject _ringChallenge; // 0x28
	private GameObject _panelNormal; // 0x30
	private GameObject _panelRift; // 0x38
	private GameObject _panelChallenge; // 0x40
	private RectTransform _dayAngle; // 0x48
	private GameObject _panelSettleDay; // 0x50
	private GameObject _panelNormalDay; // 0x58
	private CanvasGroup _panelCrossDay; // 0x60
	private CanvasGroup _panelDownContent; // 0x68
	private GameObject _normalCrossDay; // 0x70
	private GameObject _normalRiftCrossDay; // 0x78
	private GameObject _riftSettleCrossDay; // 0x80
	private GameObject _panelRiftReserved; // 0x88
	private GameObject _panelRiftQuestSucc; // 0x90
	private GameObject _panelRiftQuestFail; // 0x98
	private Text _day; // 0xa0
	private Text _maxDay; // 0xa8
	private SimpleLayoutContent _decisionContent; // 0xb0
	private UIBlendRTImage _bkgBlur; // 0xb8
	private UIAnimationLocation _switchAnim; // 0xc0
	private GameObject _panelNormalBkg; // 0xd0
	private GameObject _panelEmergencyBkg; // 0xd8
	private Color _normalTextIconColor; // 0xe0
	private Color _emergencyTextIconColor; // 0xf0
	private Graphic[] _emergencyColorGraphics; // 0x100
	private Button _buttonSphereCrossDay; // 0x108
	private Button _buttonSphereNormal; // 0x110
	private Text _textDaySurvive; // 0x118
	private Boolean m_isInited; // 0x120
	private Adapter m_adapter; // 0x128
	private UIPageFinder m_pageFinder; // 0x130
	private FadeTween m_crossDayTween; // 0x140
	private SandboxV2DungeonViewModel m_cachedViewModel; // 0x148
	public Action onContentClick; // 0x150
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderRing; // 0x8
	private static DelegateBridge __Hotfix0__RenderTip; // 0x10
	private static DelegateBridge __Hotfix0__RenderCrossDay; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_OnBtnGameflowPanelClicked; // 0x28
	private static DelegateBridge __Hotfix0_OnSphereContentClick; // 0x30
	private static DelegateBridge __Hotfix0_TutorialOnly_GetCrossDayBtnGo; // 0x38
	private static DelegateBridge __Hotfix0_TutorialOnly_GetSphereBtnGo; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x254dc6c VA: 0x7594b65c6c
	public Void Render(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x254ed60 VA: 0x7594b66d60
	private Void _RenderRing(Mode renderMode, Single daySeasonAngle) { }
	// RVA: 0x254ebdc VA: 0x7594b66bdc
	private Void _RenderTip(Mode renderMode, Boolean isRiftReservated, Boolean isRiftMainFail, Boolean isRiftMainFinish) { }
	// RVA: 0x254ef2c VA: 0x7594b66f2c
	private Void _RenderCrossDay(Mode renderMode, Boolean isSettleDay, Boolean isCrossDay, Boolean isRiftReservated, Boolean isFastMode, Boolean isEmergency) { }
	// RVA: 0x254ea1c VA: 0x7594b66a1c
	private Void _InitIfNot() { }
	// RVA: 0x254f260 VA: 0x7594b67260
	public Void OnBtnGameflowPanelClicked() { }
	// RVA: 0x254f314 VA: 0x7594b67314
	public Void OnSphereContentClick() { }
	// RVA: 0x254e380 VA: 0x7594b66380
	public GameObject TutorialOnly_GetCrossDayBtnGo() { }
	// RVA: 0x254e294 VA: 0x7594b66294
	public GameObject TutorialOnly_GetSphereBtnGo() { }
	// RVA: 0x254f398 VA: 0x7594b67398
	public Void .ctor() { }
}
```