# Main10ZoneRecordCommonView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main10`


## Fields

- `SimpleLayoutContent _content`

- `RectTransform _coverPanel`

- `GameObject _imgCoverUnlocked`

- `Text _normalCount`

- `Text _easyCount`

- `Text _toughCount`

- `Text _noteTitle`

- `Text _noteDesc`

- `RectTransform _notePanel`

- `GameObject _imgNoteUnlocked`

- `GameObject _blankDesc`

- `Image _imgEasyPic`

- `Image _imgNormalPic`

- `RectTransform _imgToughContainer`

- `Button _btnNext`

- `Button _btnPrev`

- `Button _btnNormalNote`

- `Button _btnToughNote`

- `RectTransform _rectRewardPartParent`

- `ZoneRecordRewardContentView _rewardContentPrefab`

- `Text _unlockTips`

- `UIAnimationLocation _picWithTipsSwitchAnim`

- `UIAnimationLocation _onlyPicSwitchAnim`

- `Action onClaimAllRewardClick`

- `Boolean m_isInited`

- `Main10ZoneRecordGroupViewModel m_cachedViewModel`

- `UIPage m_page`

- `AnimationSwitchTween m_unlockSwitch`

- `AnimationSwitchTween m_picSwitch`

- `ZoneRecordRewardContentView m_rewardContentView`

- `Main10ZoneRecordController <controller>k__BackingField`


## Properties

- `Main10ZoneRecordController controller`


## Methods

- `Main10ZoneRecordController get_controller()`

- `Void set_controller(Main10ZoneRecordController)`

- `Void Init(UIPage)`

- `Void _InitIfNot()`

- `AnimationSwitchTween _EnsureUnlockSwitch()`

- `Void _EnsureUnlockItemStatus()`

- `AnimationSwitchTween _EnsurePicOnlySwitch()`

- `Void PlayUnlockTips()`

- `Void HideUnlockTips()`

- `Void EventOnUnlockedPicSwitch()`

- `Void _RenderContent()`

- `Void _OnContentEvent(String)`

- `Void _Render(ZoneRecordGroupViewModel)`

- `Void _RefreshBtnStatus()`

- `Void _RenderNotePart()`

- `Void _RenderNoteReward()`

- `Void _RenderCoverPart()`

- `Void _RenderRewardStatus(ZoneRecordGroupViewModel)`

- `Void _RenderDiffRewards(Text, DiffRewardStatus)`

- `Void _InitNote()`

- `Void _TryLoadPic(Image, ZoneRecordRewardViewModel)`

- `GameObject _TryLoadToughPicPrefab(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main10
public class Main10ZoneRecordCommonView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _content; // 0x20
	private RectTransform _coverPanel; // 0x28
	private GameObject _imgCoverUnlocked; // 0x30
	private Text _normalCount; // 0x38
	private Text _easyCount; // 0x40
	private Text _toughCount; // 0x48
	private Text _noteTitle; // 0x50
	private Text _noteDesc; // 0x58
	private RectTransform _notePanel; // 0x60
	private GameObject _imgNoteUnlocked; // 0x68
	private GameObject _blankDesc; // 0x70
	private Image _imgEasyPic; // 0x78
	private Image _imgNormalPic; // 0x80
	private RectTransform _imgToughContainer; // 0x88
	private Button _btnNext; // 0x90
	private Button _btnPrev; // 0x98
	private Button _btnNormalNote; // 0xa0
	private Button _btnToughNote; // 0xa8
	private RectTransform _rectRewardPartParent; // 0xb0
	private ZoneRecordRewardContentView _rewardContentPrefab; // 0xb8
	private Text _unlockTips; // 0xc0
	private UIAnimationLocation _picWithTipsSwitchAnim; // 0xc8
	private UIAnimationLocation _onlyPicSwitchAnim; // 0xd8
	public Action`1 eventOnContentClick; // 0xe8
	public Action onClaimAllRewardClick; // 0xf0
	private Boolean m_isInited; // 0xf8
	private Main10ZoneRecordGroupViewModel m_cachedViewModel; // 0x100
	private UIPage m_page; // 0x108
	private AnimationSwitchTween m_unlockSwitch; // 0x110
	private AnimationSwitchTween m_picSwitch; // 0x118
	private ZoneRecordRewardContentView m_rewardContentView; // 0x120
	private Main10ZoneRecordController <controller>k__BackingField; // 0x128
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__EnsureUnlockSwitch; // 0x20
	private static DelegateBridge __Hotfix0__EnsureUnlockItemStatus; // 0x28
	private static DelegateBridge __Hotfix0__EnsurePicOnlySwitch; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge __Hotfix0_PlayUnlockTips; // 0x40
	private static DelegateBridge __Hotfix0_HideUnlockTips; // 0x48
	private static DelegateBridge __Hotfix0_EventOnUnlockedPicSwitch; // 0x50
	private static DelegateBridge __Hotfix0__RenderContent; // 0x58
	private static DelegateBridge __Hotfix0__OnContentEvent; // 0x60
	private static DelegateBridge __Hotfix0__Render; // 0x68
	private static DelegateBridge __Hotfix0__RefreshBtnStatus; // 0x70
	private static DelegateBridge __Hotfix0__RenderNotePart; // 0x78
	private static DelegateBridge __Hotfix0__RenderNoteReward; // 0x80
	private static DelegateBridge __Hotfix0__RenderCoverPart; // 0x88
	private static DelegateBridge __Hotfix0__RenderRewardStatus; // 0x90
	private static DelegateBridge __Hotfix0__RenderDiffRewards; // 0x98
	private static DelegateBridge __Hotfix0__InitNote; // 0xa0
	private static DelegateBridge __Hotfix0__TryLoadPic; // 0xa8
	private static DelegateBridge __Hotfix0__TryLoadToughPicPrefab; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public Main10ZoneRecordController controller { get; set; }

	// RVA: 0x2fdc2c8 VA: 0x75955f42c8
	public Main10ZoneRecordController get_controller() { }
	// RVA: 0x2fdc330 VA: 0x75955f4330
	public Void set_controller(Main10ZoneRecordController value) { }
	// RVA: 0x2fdc3b4 VA: 0x75955f43b4
	public Void Init(UIPage page) { }
	// RVA: 0x2fdc438 VA: 0x75955f4438
	private Void _InitIfNot() { }
	// RVA: 0x2fdc570 VA: 0x75955f4570
	private AnimationSwitchTween _EnsureUnlockSwitch() { }
	// RVA: 0x2fdc66c VA: 0x75955f466c
	private Void _EnsureUnlockItemStatus() { }
	// RVA: 0x2fdc6dc VA: 0x75955f46dc
	private AnimationSwitchTween _EnsurePicOnlySwitch() { }
	// RVA: 0x2fdc7d8 VA: 0x75955f47d8
	public override Void OnValueChanged(Main10ZoneRecordViewProperty property) { }
	// RVA: 0x2fdcb3c VA: 0x75955f4b3c
	public Void PlayUnlockTips() { }
	// RVA: 0x2fdcbc8 VA: 0x75955f4bc8
	public Void HideUnlockTips() { }
	// RVA: 0x2fdcc44 VA: 0x75955f4c44
	public Void EventOnUnlockedPicSwitch() { }
	// RVA: 0x2fdc88c VA: 0x75955f488c
	private Void _RenderContent() { }
	// RVA: 0x2fdcd84 VA: 0x75955f4d84
	private Void _OnContentEvent(String recordId) { }
	// RVA: 0x2fdc9c0 VA: 0x75955f49c0
	private Void _Render(ZoneRecordGroupViewModel viewModel) { }
	// RVA: 0x2fdd164 VA: 0x75955f5164
	private Void _RefreshBtnStatus() { }
	// RVA: 0x2fdcf30 VA: 0x75955f4f30
	private Void _RenderNotePart() { }
	// RVA: 0x2fdd558 VA: 0x75955f5558
	private Void _RenderNoteReward() { }
	// RVA: 0x2fdce24 VA: 0x75955f4e24
	private Void _RenderCoverPart() { }
	// RVA: 0x2fdd5d0 VA: 0x75955f55d0
	private Void _RenderRewardStatus(ZoneRecordGroupViewModel viewModel) { }
	// RVA: 0x2fdd6c4 VA: 0x75955f56c4
	private Void _RenderDiffRewards(Text cntText, DiffRewardStatus status) { }
	// RVA: 0x2fdd274 VA: 0x75955f5274
	private Void _InitNote() { }
	// RVA: 0x2fdd358 VA: 0x75955f5358
	private Void _TryLoadPic(Image img, ZoneRecordRewardViewModel viewModel) { }
	// RVA: 0x2fdd444 VA: 0x75955f5444
	private GameObject _TryLoadToughPicPrefab(String prefabName) { }
	// RVA: 0x2fdd7e0 VA: 0x75955f57e0
	public Void .ctor() { }
}
```