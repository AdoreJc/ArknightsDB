# DynIllustStartMgr

**Namespace:** `Torappu.UI`


## Fields

- `Camera _cameraUI`

- `Camera _cameraBack`

- `GameObject _btnSkipGacha`

- `GameObject _btnSkipNormal`

- `GameObject _panelSkip`

- `GameObject _raycastBlocker`

- `CanvasGroup _canvasMask`

- `Image _imgMask`

- `Transform _instHolder`

- `DynIllustStartPlay m_activeInst`

- `DynIllustStartPlay m_activeRes`

- `Boolean m_isPlaying`

- `Boolean m_isSkipped`

- `SkipManager m_skipManager`

- `CharVoiceManager m_charVoiceManager`

- `UISwitchTween m_switchTweenSkip`


## Properties

- `Boolean isPlaying`


## Methods

- `Boolean get_isPlaying()`

- `IEnumerator _ShowBlackMask(Boolean, Color)`

- `Void _HideBlackMask(Action)`

- `Void _InitSwitchTween()`

- `Coroutine PlayDynEntrance(Param)`

- `IEnumerator _PlayDynEntranceCoroutine(Param)`

- `Boolean TryFetchAndAddCameras(List`1)`

- `Void _ClearDynEntrance()`

- `Void _DefaultPlayCharVoice(CharUISkinStruct)`

- `Void _DefaultPlayDynIllustStart(CharUISkinStruct)`

- `Void _StopBGM()`

- `Void _ResumeBGM()`

- `Int32 _GetBGMInstId()`

- `Void OnBtnSkipClicked()`

- `Void OnScreenClicked()`

- `Void <_PlayDynEntranceCoroutine>b__36_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class DynIllustStartMgr : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private const Single DYN_ENTRANCE_INSTANCE_INIT_POS_Z; // 0x0
	private const Single DYN_ENTRANCE_MASK_TWEEN_DURATION; // 0x0
	private const Single DYN_ENTRANCE_AUDIO_FADE_TIME; // 0x0
	private static UInt32 s_loginKey; // 0x0
	private Camera _cameraUI; // 0x18
	private Camera _cameraBack; // 0x20
	private GameObject _btnSkipGacha; // 0x28
	private GameObject _btnSkipNormal; // 0x30
	private GameObject _panelSkip; // 0x38
	private GameObject _raycastBlocker; // 0x40
	private CanvasGroup _canvasMask; // 0x48
	private Image _imgMask; // 0x50
	private Transform _instHolder; // 0x58
	private DynIllustStartPlay m_activeInst; // 0x60
	private DynIllustStartPlay m_activeRes; // 0x68
	private Boolean m_isPlaying; // 0x70
	private Boolean m_isSkipped; // 0x71
	private SkipManager m_skipManager; // 0x78
	private CharVoiceManager m_charVoiceManager; // 0x80
	private UISwitchTween m_switchTweenSkip; // 0x88
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__ShowBlackMask; // 0x20
	private static DelegateBridge __Hotfix0__HideBlackMask; // 0x28
	private static DelegateBridge __Hotfix0__InitSwitchTween; // 0x30
	private static DelegateBridge __Hotfix0_PlayDynEntrance; // 0x38
	private static DelegateBridge __Hotfix0__PlayDynEntranceCoroutine; // 0x40
	private static DelegateBridge __Hotfix0_TryFetchAndAddCameras; // 0x48
	private static DelegateBridge __Hotfix0__ClearDynEntrance; // 0x50
	private static DelegateBridge __Hotfix0__DefaultPlayCharVoice; // 0x58
	private static DelegateBridge __Hotfix0__DefaultPlayDynIllustStart; // 0x60
	private static DelegateBridge __Hotfix0__StopBGM; // 0x68
	private static DelegateBridge __Hotfix0__ResumeBGM; // 0x70
	private static DelegateBridge __Hotfix0__GetBGMInstId; // 0x78
	private static DelegateBridge __Hotfix0_SkinShopOnlyCheckPlayDynEntrance; // 0x80
	private static DelegateBridge __Hotfix0_CheckPlayDynEntrance; // 0x88
	private static DelegateBridge __Hotfix0_GetPlayDynEntranceErrMsg; // 0x90
	private static DelegateBridge __Hotfix0_CheckPlayDynEntranceForLogin; // 0x98
	private static DelegateBridge __Hotfix0_MarkHomePageRouted; // 0xa0
	private static DelegateBridge __Hotfix0_MarkPlayDynEntranceForLogin; // 0xa8
	private static DelegateBridge __Hotfix0_OnBtnSkipClicked; // 0xb0
	private static DelegateBridge __Hotfix0_OnScreenClicked; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public Boolean isPlaying { get; }

	// RVA: 0x2113fa8 VA: 0x759472bfa8
	public Boolean get_isPlaying() { }
	// RVA: 0x2114010 VA: 0x759472c010
	protected override Void OnInit() { }
	// RVA: 0x2114078 VA: 0x759472c078
	protected override Void OnDestroy() { }
	// RVA: 0x2114284 VA: 0x759472c284
	private IEnumerator _ShowBlackMask(Boolean fastMode, Color color) { }
	// RVA: 0x21143b4 VA: 0x759472c3b4
	private Void _HideBlackMask(Action onComplete) { }
	// RVA: 0x2114528 VA: 0x759472c528
	private Void _InitSwitchTween() { }
	// RVA: 0x211461c VA: 0x759472c61c
	public Coroutine PlayDynEntrance(Param param) { }
	// RVA: 0x21146ac VA: 0x759472c6ac
	private IEnumerator _PlayDynEntranceCoroutine(Param param) { }
	// RVA: 0x21147a4 VA: 0x759472c7a4
	public Boolean TryFetchAndAddCameras(List`1 cameras) { }
	// RVA: 0x2114100 VA: 0x759472c100
	private Void _ClearDynEntrance() { }
	// RVA: 0x2114c94 VA: 0x759472cc94
	private Void _DefaultPlayCharVoice(CharUISkinStruct skin) { }
	// RVA: 0x2114e18 VA: 0x759472ce18
	private Void _DefaultPlayDynIllustStart(CharUISkinStruct skin) { }
	// RVA: 0x211500c VA: 0x759472d00c
	private Void _StopBGM() { }
	// RVA: 0x211515c VA: 0x759472d15c
	private Void _ResumeBGM() { }
	// RVA: 0x21150f0 VA: 0x759472d0f0
	private Int32 _GetBGMInstId() { }
	// RVA: 0x2115240 VA: 0x759472d240
	public static CheckPlayDynEntranceRes SkinShopOnlyCheckPlayDynEntrance() { }
	// RVA: 0x211538c VA: 0x759472d38c
	public static CheckPlayDynEntranceRes CheckPlayDynEntrance(Boolean passive, Boolean isHomePage) { }
	// RVA: 0x2115520 VA: 0x759472d520
	public static String GetPlayDynEntranceErrMsg(CheckPlayDynEntranceRes errocde) { }
	// RVA: 0x2115608 VA: 0x759472d608
	public static Boolean CheckPlayDynEntranceForLogin(String dynIllustId) { }
	// RVA: 0x21157b0 VA: 0x759472d7b0
	public static Void MarkHomePageRouted() { }
	// RVA: 0x2115844 VA: 0x759472d844
	public static Void MarkPlayDynEntranceForLogin(String dynIllustId) { }
	// RVA: 0x2115910 VA: 0x759472d910
	public Void OnBtnSkipClicked() { }
	// RVA: 0x2115a0c VA: 0x759472da0c
	public Void OnScreenClicked() { }
	// RVA: 0x2115aa0 VA: 0x759472daa0
	public Void .ctor() { }
	// RVA: 0x2115b30 VA: 0x759472db30
	private Void <_PlayDynEntranceCoroutine>b__36_0() { }
}
```