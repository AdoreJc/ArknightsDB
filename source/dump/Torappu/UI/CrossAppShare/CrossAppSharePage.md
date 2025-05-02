# CrossAppSharePage

**Namespace:** `Torappu.UI.CrossAppShare`


## Fields

- `RectTransform _remakeContent`

- `UIRenderTextureImage _background`

- `Camera _remakeCamera`

- `Canvas _remakeCanvas`

- `UIAnimationLocation _flashInAnim`

- `UIAnimationLocation _flashOutAnim`

- `CanvasGroup _pageCanvasGroup`

- `CrossAppShareController m_controller`

- `Tween m_flashInTween`

- `Tween m_flashOutTween`

- `Boolean m_isWorking`


## Methods

- `Void _StartShare(InputParam)`

- `IEnumerator _ShareCorot(InputOption)`

- `Void _OnClosePanel(Action)`

- `Void _ConfirmCrossAppShareMission(String, Action)`

- `Void ExitShareWithoutUnRegister()`

- `IEnumerator PlayFlashInAnim()`

- `IEnumerator PlayFlashOutAnim()`

- `Void _ReceiveRewards(List`1)`

- `Void _BindBackPressWhenSDKDisabled()`

- `IEnumerator <>n__0(Boolean)`

- `IEnumerator <>n__1(Boolean)`

- `Void <_StartShare>b__17_0()`

- `Void <_ReceiveRewards>b__25_0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean)`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrossAppShare
public class CrossAppSharePage : UIPage
{
	private const Single DEFAULT_FADE_DURATION; // 0x0
	private const Single DEFAULT_HIDE_ALPHA; // 0x0
	private RectTransform _remakeContent; // 0xd0
	private UIRenderTextureImage _background; // 0xd8
	private Camera _remakeCamera; // 0xe0
	private Canvas _remakeCanvas; // 0xe8
	private UIAnimationLocation _flashInAnim; // 0xf0
	private UIAnimationLocation _flashOutAnim; // 0x100
	private CanvasGroup _pageCanvasGroup; // 0x110
	private CrossAppShareController m_controller; // 0x118
	private Tween m_flashInTween; // 0x120
	private Tween m_flashOutTween; // 0x128
	private Boolean m_isWorking; // 0x130
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__StartShare; // 0x18
	private static DelegateBridge __Hotfix0__ShareCorot; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__OnClosePanel; // 0x30
	private static DelegateBridge __Hotfix0__ConfirmCrossAppShareMission; // 0x38
	private static DelegateBridge __Hotfix0_ExitShareWithoutUnRegister; // 0x40
	private static DelegateBridge __Hotfix0_PlayFlashInAnim; // 0x48
	private static DelegateBridge __Hotfix0_PlayFlashOutAnim; // 0x50
	private static DelegateBridge __Hotfix0__ReceiveRewards; // 0x58
	private static DelegateBridge __Hotfix0__BindBackPressWhenSDKDisabled; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2bbf53c VA: 0x75951d753c
	protected override Void OnCreate(DataBundle savedInstance) { }
	// RVA: 0x2bbfad8 VA: 0x75951d7ad8
	public override IEnumerator ShowCoroutine(Boolean isFromStack) { }
	// RVA: 0x2bbfbc8 VA: 0x75951d7bc8
	protected override IEnumerator HideCoroutine(Boolean isIntoStack) { }
	// RVA: 0x2bbf620 VA: 0x75951d7620
	private Void _StartShare(InputParam inputParam) { }
	// RVA: 0x2bbfe10 VA: 0x75951d7e10
	private IEnumerator _ShareCorot(InputOption option) { }
	// RVA: 0x2bbff34 VA: 0x75951d7f34
	protected override Void OnDestroy() { }
	// RVA: 0x2bbffb8 VA: 0x75951d7fb8
	private Void _OnClosePanel(Action onFinish) { }
	// RVA: 0x2bc006c VA: 0x75951d806c
	private Void _ConfirmCrossAppShareMission(String missionId, Action onFinish) { }
	// RVA: 0x2bc03c4 VA: 0x75951d83c4
	public Void ExitShareWithoutUnRegister() { }
	// RVA: 0x2bbfcb8 VA: 0x75951d7cb8
	public IEnumerator PlayFlashInAnim() { }
	// RVA: 0x2bbfd64 VA: 0x75951d7d64
	public IEnumerator PlayFlashOutAnim() { }
	// RVA: 0x2bc0480 VA: 0x75951d8480
	private Void _ReceiveRewards(List`1 items) { }
	// RVA: 0x2bbf954 VA: 0x75951d7954
	private Void _BindBackPressWhenSDKDisabled() { }
	// RVA: 0x2bc05c0 VA: 0x75951d85c0
	public Void .ctor() { }
	// RVA: 0x2bc0630 VA: 0x75951d8630
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x2bc063c VA: 0x75951d863c
	private IEnumerator <>n__1(Boolean isIntoStack) { }
	// RVA: 0x2bc0648 VA: 0x75951d8648
	private Void <_StartShare>b__17_0() { }
	// RVA: 0x2bc064c VA: 0x75951d864c
	private Void <_ReceiveRewards>b__25_0() { }
	// RVA: 0x2bc0650 VA: 0x75951d8650
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2bc0658 VA: 0x75951d8658
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean P0) { }
	// RVA: 0x2bc0664 VA: 0x75951d8664
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean P0) { }
	// RVA: 0x2bc0670 VA: 0x75951d8670
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```