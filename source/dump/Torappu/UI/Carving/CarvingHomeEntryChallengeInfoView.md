# CarvingHomeEntryChallengeInfoView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `UIAnimationLocation _loopAnim`

- `UIAnimationLocation _lockedAnim`

- `UISpineLocation _handbookSpine`

- `GameObject _panelBestRecord`

- `Text _textBestRecord`

- `GameObject _panelInfo`

- `Text _textName`

- `Text _textDesc`

- `GameObject _panelComplete`

- `GameObject _panelLocked`

- `GameObject _panelStageLockedTips`

- `GameObject _panelTimeLockedTips`

- `Text _textUnlockTime`

- `GameObject _panelIsPlaying`

- `GameObject _panelPrevBtn`

- `GameObject _panelPrevNew`

- `GameObject _panelNextBtn`

- `GameObject _panelNextNew`

- `GameObject _panelContinueChallenge`

- `GameObject _panelPlayingTip`

- `GameObject _panelStartChallengeEnable`

- `GameObject _panelStartChallengeDisable`

- `GameObject _panelStopChallenge`

- `Tween m_loopAnim`

- `Tween m_lockedAnim`

- `Int32 m_cachedIndex`

- `UIStateFinder m_stateFinder`

- `Boolean m_hasInited`


## Methods

- `Void OnExit()`

- `Void EventOnNextBtnClicked()`

- `Void EventOnPrevBtnClicked()`

- `Void EventOnStartChallengeBtnClicked()`

- `Void EventOnSettleChallengeBtnClicked()`

- `Void EventOnHandbookBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingHomeEntryChallengeInfoView : DataBinder`1, IHotfixable
{
	private UIAnimationLocation _loopAnim; // 0x20
	private UIAnimationLocation _lockedAnim; // 0x30
	private UISpineLocation _handbookSpine; // 0x40
	private GameObject _panelBestRecord; // 0x50
	private Text _textBestRecord; // 0x58
	private GameObject _panelInfo; // 0x60
	private Text _textName; // 0x68
	private Text _textDesc; // 0x70
	private GameObject _panelComplete; // 0x78
	private GameObject _panelLocked; // 0x80
	private GameObject _panelStageLockedTips; // 0x88
	private GameObject _panelTimeLockedTips; // 0x90
	private Text _textUnlockTime; // 0x98
	private GameObject _panelIsPlaying; // 0xa0
	private GameObject _panelPrevBtn; // 0xa8
	private GameObject _panelPrevNew; // 0xb0
	private GameObject _panelNextBtn; // 0xb8
	private GameObject _panelNextNew; // 0xc0
	private GameObject _panelContinueChallenge; // 0xc8
	private GameObject _panelPlayingTip; // 0xd0
	private GameObject _panelStartChallengeEnable; // 0xd8
	private GameObject _panelStartChallengeDisable; // 0xe0
	private GameObject _panelStopChallenge; // 0xe8
	private Tween m_loopAnim; // 0xf0
	private Tween m_lockedAnim; // 0xf8
	private Int32 m_cachedIndex; // 0x100
	private UIStateFinder m_stateFinder; // 0x108
	private Boolean m_hasInited; // 0x118
	private static DelegateBridge __Hotfix0_OnExit; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_EventOnNextBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnPrevBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnStartChallengeBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnSettleChallengeBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnHandbookBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2d92178 VA: 0x75953aa178
	public Void OnExit() { }
	// RVA: 0x2d92250 VA: 0x75953aa250
	public override Void OnValueChanged(CarvingHomeEntryProperty property) { }
	// RVA: 0x2d92cb8 VA: 0x75953aacb8
	public Void EventOnNextBtnClicked() { }
	// RVA: 0x2d92d5c VA: 0x75953aad5c
	public Void EventOnPrevBtnClicked() { }
	// RVA: 0x2d92e00 VA: 0x75953aae00
	public Void EventOnStartChallengeBtnClicked() { }
	// RVA: 0x2d92ea4 VA: 0x75953aaea4
	public Void EventOnSettleChallengeBtnClicked() { }
	// RVA: 0x2d92f48 VA: 0x75953aaf48
	public Void EventOnHandbookBtnClicked() { }
	// RVA: 0x2d92834 VA: 0x75953aa834
	private Void _InitIfNot() { }
	// RVA: 0x2d92fec VA: 0x75953aafec
	public Void .ctor() { }
}
```