# HandBookInfoView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Text _nameText`

- `Text _nickText`

- `Text _drawerName`

- `Text _soundName`

- `Image _professionIcon`

- `HandBookInfoStateBean _stateBean`

- `Transform _scrollView`

- `Animator _scrollAnim`

- `Transform _lockedText`

- `HandbookInfoTextView _infoText`

- `HandBookInfoAudioView _infoAudio`

- `HandBookAvgGroupView _infoAvg`

- `HandbookLockedView _infoLocked`

- `Image _campImage`

- `GameObject _soundCrossObj`

- `GameObject _soundHotSpotObj`

- `GameObject _soundUnDownloadMaskObj`

- `GameObject _designerObj`

- `GameObject _designerHotSpotObj`

- `UnityEvent _onClickEvent`

- `UIStringEvent _onClickGroup`

- `UnityEvent _onLockEvent`

- `Boolean m_isFast`

- `Int32 m_barID`

- `Boolean m_npcAudioHideButtonFlag`

- `ProfessionSpriteHub m_professionHub`

- `UIPageFinder m_pageFinder`


## Properties

- `Boolean isFast`


## Methods

- `Void set_onAvgItemClick(Action`1)`

- `Boolean get_isFast()`

- `Void set_isFast(Boolean)`

- `HandBookButtonTab _GetButtonByIndex(Int32)`

- `Void _InitButtonState()`

- `Void OnClick(Int32)`

- `Void RenderCurrentBarId()`

- `Void OnRewardClick(Int32)`

- `Void ApplyData()`

- `Void RefreshVoiceLang()`

- `Void OnAudioPlay(Int32)`

- `Void OnEventCancelButton()`

- `Void UpdateProfessionIcon()`

- `Sprite _GetProfessionSprite(ProfessionCategory)`

- `Void _OnAvgItemClicked(String)`

- `Void _RefreshVoiceBarStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoView : MonoBehaviour, IHotfixable
{
	private Text _nameText; // 0x18
	private Text _nickText; // 0x20
	private Text _drawerName; // 0x28
	private Text _soundName; // 0x30
	private Image _professionIcon; // 0x38
	private HandBookInfoStateBean _stateBean; // 0x40
	private Transform _scrollView; // 0x48
	private Animator _scrollAnim; // 0x50
	private Transform _lockedText; // 0x58
	private HandbookInfoTextView _infoText; // 0x60
	private HandBookInfoAudioView _infoAudio; // 0x68
	private HandBookAvgGroupView _infoAvg; // 0x70
	private HandbookLockedView _infoLocked; // 0x78
	private HandBookButtonTab[] _buttons; // 0x80
	private HandBookButtonTab[] _npcLockedButtons; // 0x88
	private Image _campImage; // 0x90
	private GameObject _soundCrossObj; // 0x98
	private GameObject _soundHotSpotObj; // 0xa0
	private GameObject _soundUnDownloadMaskObj; // 0xa8
	private GameObject _designerObj; // 0xb0
	private GameObject _designerHotSpotObj; // 0xb8
	private UnityEvent _onClickEvent; // 0xc0
	private UIStringEvent _onClickGroup; // 0xc8
	private UnityEvent _onLockEvent; // 0xd0
	private Action`1 <onAvgItemClick>k__BackingField; // 0xd8
	private Boolean m_isFast; // 0xe0
	private Int32 m_barID; // 0xe4
	private const Int32 NPCLOCKEDBUTTONINDEX; // 0x0
	private Boolean m_npcAudioHideButtonFlag; // 0xe8
	private List`1 m_objList; // 0xf0
	private List`1 m_lockedList; // 0xf8
	private List`1 m_audioList; // 0x100
	private List`1 m_avgList; // 0x108
	private ProfessionSpriteHub m_professionHub; // 0x110
	private UIPageFinder m_pageFinder; // 0x118
	private static DelegateBridge __Hotfix0_get_onAvgItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onAvgItemClick; // 0x8
	private static DelegateBridge __Hotfix0_get_isFast; // 0x10
	private static DelegateBridge __Hotfix0_set_isFast; // 0x18
	private static DelegateBridge __Hotfix0__GetButtonByIndex; // 0x20
	private static DelegateBridge __Hotfix0__InitButtonState; // 0x28
	private static DelegateBridge __Hotfix0_OnClick; // 0x30
	private static DelegateBridge __Hotfix0_RenderCurrentBarId; // 0x38
	private static DelegateBridge __Hotfix0_OnRewardClick; // 0x40
	private static DelegateBridge __Hotfix0_ApplyData; // 0x48
	private static DelegateBridge __Hotfix0_RefreshVoiceLang; // 0x50
	private static DelegateBridge __Hotfix0_OnAudioPlay; // 0x58
	private static DelegateBridge __Hotfix0_OnEventCancelButton; // 0x60
	private static DelegateBridge __Hotfix0_UpdateProfessionIcon; // 0x68
	private static DelegateBridge __Hotfix0__GetProfessionSprite; // 0x70
	private static DelegateBridge __Hotfix0__OnAvgItemClicked; // 0x78
	private static DelegateBridge __Hotfix0__RefreshVoiceBarStatus; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	private Action`1 onAvgItemClick { get; set; }
	public Boolean isFast { get; set; }

	// RVA: 0x2eaeff8 VA: 0x75954c6ff8
	private Action`1 get_onAvgItemClick() { }
	// RVA: 0x2ea1f5c VA: 0x75954b9f5c
	public Void set_onAvgItemClick(Action`1 value) { }
	// RVA: 0x2eaf060 VA: 0x75954c7060
	public Boolean get_isFast() { }
	// RVA: 0x2ea2340 VA: 0x75954ba340
	public Void set_isFast(Boolean value) { }
	// RVA: 0x2eaf0c8 VA: 0x75954c70c8
	private HandBookButtonTab _GetButtonByIndex(Int32 index) { }
	// RVA: 0x2eaf21c VA: 0x75954c721c
	private Void _InitButtonState() { }
	// RVA: 0x2ea2240 VA: 0x75954ba240
	public Void OnClick(Int32 stateID) { }
	// RVA: 0x2ea23c0 VA: 0x75954ba3c0
	public Void RenderCurrentBarId() { }
	// RVA: 0x2eafd84 VA: 0x75954c7d84
	public Void OnRewardClick(Int32 index) { }
	// RVA: 0x2ea57e0 VA: 0x75954bd7e0
	public Void ApplyData() { }
	// RVA: 0x2ea37fc VA: 0x75954bb7fc
	public Void RefreshVoiceLang() { }
	// RVA: 0x2eac910 VA: 0x75954c4910
	public Void OnAudioPlay(Int32 id) { }
	// RVA: 0x2eafef4 VA: 0x75954c7ef4
	public Void OnEventCancelButton() { }
	// RVA: 0x2ea36b8 VA: 0x75954bb6b8
	public Void UpdateProfessionIcon() { }
	// RVA: 0x2eaff78 VA: 0x75954c7f78
	private Sprite _GetProfessionSprite(ProfessionCategory profession) { }
	// RVA: 0x2eb0154 VA: 0x75954c8154
	private Void _OnAvgItemClicked(String storyId) { }
	// RVA: 0x2eb020c VA: 0x75954c820c
	private Void _RefreshVoiceBarStatus() { }
	// RVA: 0x2eb0300 VA: 0x75954c8300
	public Void .ctor() { }
}
```