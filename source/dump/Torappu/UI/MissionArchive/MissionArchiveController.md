# MissionArchiveController

**Namespace:** `Torappu.UI.MissionArchive`


## Fields

- `RectTransform _backRect`

- `UIAnimationLocation _entryAnimation`

- `MissionArchiveMainView _mainView`

- `MissionArchivePlayView _playView`

- `MissionArchiveHintView _hintView`

- `MissionArchiveDataServiceProxy _dataServiceProxy`

- `CanvasGroup _contentGroup`

- `CanvasGroup _maskGroup`

- `GameObject _rtContentPrefab`

- `AudioConfig _audioConfig`

- `String m_topicId`

- `MissionArchiveViewProperty m_property`

- `Builder m_entryTweenBuilder`

- `UIAnimationTween m_entryTween`

- `MissionArchivePlayer m_player`

- `FadeSwitchTween m_contentSwitchTween`

- `FadeSwitchTween m_maskSwitchTween`

- `MissionArchiveNodeViewModel m_cachedSelectedNode`

- `Coroutine m_switchCoroutine`

- `Tween m_nodeSelectTween`

- `Tween m_playShowTween`

- `Tween m_playHideTween`

- `Boolean m_freezeBack`

- `Int64 m_musicInstId`

- `Boolean m_loopFxForHiddenPlayed`

- `MissionArchivePage <page>k__BackingField`


## Properties

- `MissionArchivePage page`

- `FadeSwitchTween contentSwitchTween`

- `FadeSwitchTween maskSwitchTween`

- `GameObject rtContentPrefab`


## Methods

- `MissionArchivePage get_page()`

- `Void set_page(MissionArchivePage)`

- `FadeSwitchTween get_contentSwitchTween()`

- `FadeSwitchTween get_maskSwitchTween()`

- `GameObject get_rtContentPrefab()`

- `Void Init(String, MissionArchiveExteriorPlayer)`

- `Void OnShow()`

- `Void OnBackEvent()`

- `Void _SelectNode(String)`

- `Void _PlayHiddenClips()`

- `Void _Replay()`

- `Void _OnNodeRewardResponse(IMissionArchiveClaimNodeRewardResponse)`

- `IEnumerator _ShowPlayNodeCoroutine(IMissionArchiveClaimNodeRewardResponse)`

- `IEnumerator _ShowPlayNodeCoroutine()`

- `IEnumerator _ShowPlayHiddenCoroutine()`

- `IEnumerator _HidePlayCoroutine()`

- `Void _PlayBGM()`

- `Void _RemoveBGM()`

- `Void _PlayLoopFxForHiddenIfNeed()`

- `Void _StopLoopFxForHiddenIfNeed()`

- `Void <OnShow>b__39_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.MissionArchive
public class MissionArchiveController : MonoBehaviour, IHotfixable
{
	private const Single FADE_IN_DURATION; // 0x0
	private RectTransform _backRect; // 0x18
	private UIAnimationLocation _entryAnimation; // 0x20
	private MissionArchiveMainView _mainView; // 0x30
	private MissionArchivePlayView _playView; // 0x38
	private MissionArchiveHintView _hintView; // 0x40
	private MissionArchiveDataServiceProxy _dataServiceProxy; // 0x48
	private CanvasGroup _contentGroup; // 0x50
	private CanvasGroup _maskGroup; // 0x58
	private UICommonPageEffectHolder[] _effectHolders; // 0x60
	private GameObject _rtContentPrefab; // 0x68
	public AudioConfig _audioConfig; // 0x70
	private String m_topicId; // 0x88
	private MissionArchiveViewProperty m_property; // 0x90
	private Builder m_entryTweenBuilder; // 0x98
	private UIAnimationTween m_entryTween; // 0xc0
	private MissionArchivePlayer m_player; // 0xc8
	private FadeSwitchTween m_contentSwitchTween; // 0xd0
	private FadeSwitchTween m_maskSwitchTween; // 0xd8
	private MissionArchiveNodeViewModel m_cachedSelectedNode; // 0xe0
	private Coroutine m_switchCoroutine; // 0xe8
	private Tween m_nodeSelectTween; // 0xf0
	private Tween m_playShowTween; // 0xf8
	private Tween m_playHideTween; // 0x100
	private Boolean m_freezeBack; // 0x108
	private Int64 m_musicInstId; // 0x110
	private Boolean m_loopFxForHiddenPlayed; // 0x118
	private MissionArchivePage <page>k__BackingField; // 0x120
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_get_contentSwitchTween; // 0x10
	private static DelegateBridge __Hotfix0_get_maskSwitchTween; // 0x18
	private static DelegateBridge __Hotfix0_get_rtContentPrefab; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_OnShow; // 0x30
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x38
	private static DelegateBridge __Hotfix0__SelectNode; // 0x40
	private static DelegateBridge __Hotfix0__PlayHiddenClips; // 0x48
	private static DelegateBridge __Hotfix0__Replay; // 0x50
	private static DelegateBridge __Hotfix0__OnNodeRewardResponse; // 0x58
	private static DelegateBridge __Hotfix0__ShowPlayNodeCoroutine; // 0x60
	private static DelegateBridge __Hotfix1__ShowPlayNodeCoroutine; // 0x68
	private static DelegateBridge __Hotfix0__ShowPlayHiddenCoroutine; // 0x70
	private static DelegateBridge __Hotfix0__HidePlayCoroutine; // 0x78
	private static DelegateBridge __Hotfix0__PlayBGM; // 0x80
	private static DelegateBridge __Hotfix0__RemoveBGM; // 0x88
	private static DelegateBridge __Hotfix0__PlayLoopFxForHiddenIfNeed; // 0x90
	private static DelegateBridge __Hotfix0__StopLoopFxForHiddenIfNeed; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	private MissionArchivePage page { get; set; }
	public FadeSwitchTween contentSwitchTween { get; }
	public FadeSwitchTween maskSwitchTween { get; }
	public GameObject rtContentPrefab { get; }

	// RVA: 0x2727958 VA: 0x7594d3f958
	private MissionArchivePage get_page() { }
	// RVA: 0x27279c0 VA: 0x7594d3f9c0
	public Void set_page(MissionArchivePage value) { }
	// RVA: 0x2727a44 VA: 0x7594d3fa44
	public FadeSwitchTween get_contentSwitchTween() { }
	// RVA: 0x2727aac VA: 0x7594d3faac
	public FadeSwitchTween get_maskSwitchTween() { }
	// RVA: 0x2727b14 VA: 0x7594d3fb14
	public GameObject get_rtContentPrefab() { }
	// RVA: 0x2727b7c VA: 0x7594d3fb7c
	public Void Init(String topicId, MissionArchiveExteriorPlayer exteriorPlayer) { }
	// RVA: 0x2728858 VA: 0x7594d40858
	public Void OnShow() { }
	// RVA: 0x2728e50 VA: 0x7594d40e50
	public Void OnBackEvent() { }
	// RVA: 0x27294a0 VA: 0x7594d414a0
	private Void _SelectNode(String nodeId) { }
	// RVA: 0x27298d4 VA: 0x7594d418d4
	private Void _PlayHiddenClips() { }
	// RVA: 0x2729abc VA: 0x7594d41abc
	private Void _Replay() { }
	// RVA: 0x2729e8c VA: 0x7594d41e8c
	private Void _OnNodeRewardResponse(IMissionArchiveClaimNodeRewardResponse response) { }
	// RVA: 0x2729f88 VA: 0x7594d41f88
	private IEnumerator _ShowPlayNodeCoroutine(IMissionArchiveClaimNodeRewardResponse response) { }
	// RVA: 0x2729770 VA: 0x7594d41770
	private IEnumerator _ShowPlayNodeCoroutine() { }
	// RVA: 0x2729a10 VA: 0x7594d41a10
	private IEnumerator _ShowPlayHiddenCoroutine() { }
	// RVA: 0x27292a4 VA: 0x7594d412a4
	private IEnumerator _HidePlayCoroutine() { }
	// RVA: 0x2728c4c VA: 0x7594d40c4c
	private Void _PlayBGM() { }
	// RVA: 0x2729350 VA: 0x7594d41350
	private Void _RemoveBGM() { }
	// RVA: 0x2728d6c VA: 0x7594d40d6c
	private Void _PlayLoopFxForHiddenIfNeed() { }
	// RVA: 0x27293ec VA: 0x7594d413ec
	private Void _StopLoopFxForHiddenIfNeed() { }
	// RVA: 0x272a0f8 VA: 0x7594d420f8
	public Void .ctor() { }
	// RVA: 0x272a2f4 VA: 0x7594d422f4
	private Void <OnShow>b__39_0() { }
}
```