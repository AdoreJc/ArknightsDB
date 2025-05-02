# CrisisV2SettleView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `UIAtlasImage _imgSeasonBg`

- `ScorePanel _scorePanel`

- `NewCompletePanel _newCompletePanel`

- `ResultPanel _resultPanel`

- `InternalState m_state`

- `CrisisV2SettleViewModel m_viewModel`

- `Coroutine m_updateStateCoroutine`

- `Coroutine m_settleEnterSoundCoroutine`

- `Coroutine m_newCompleteItemSoundCoroutine`

- `Boolean m_hasInited`

- `Action <onCloseClicked>k__BackingField`

- `ILoadAsset <assetLoader>k__BackingField`

- `UICharacterIllustLoader <illustLoader>k__BackingField`


## Properties

- `Action onCloseClicked`

- `ILoadAsset assetLoader`

- `UICharacterIllustLoader illustLoader`


## Methods

- `Action get_onCloseClicked()`

- `Void set_onCloseClicked(Action)`

- `ILoadAsset get_assetLoader()`

- `Void set_assetLoader(ILoadAsset)`

- `UICharacterIllustLoader get_illustLoader()`

- `Void set_illustLoader(UICharacterIllustLoader)`

- `Void Render(CrisisV2SettleViewModel)`

- `Void StartAnimation()`

- `Void StopAnimation()`

- `Void _InitIfNot()`

- `IEnumerator _UpdateStateCoroutine()`

- `Void _OnScoreEnterAnimPlayFinish()`

- `Void _OnScoreNewAnimPlayFinish()`

- `Void _OnScoreResultAnimPlayFinish()`

- `Void _OnNewCompleteAnimPlayFinish()`

- `Void _OnResultEnterAnimPlayFinish()`

- `Void _CloseView()`

- `Void OnDestroy()`

- `Void EventOnPageClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2SettleView : MonoBehaviour, IHotfixable
{
	private const Single SETTLEMENT_REWARD_APPEAR; // 0x0
	private const Single SETTLEMENT_NEW_COMPLETE_ITEM; // 0x0
	private UIAtlasImage _imgSeasonBg; // 0x18
	private ScorePanel _scorePanel; // 0x20
	private NewCompletePanel _newCompletePanel; // 0x28
	private ResultPanel _resultPanel; // 0x30
	private InternalState m_state; // 0x38
	private CrisisV2SettleViewModel m_viewModel; // 0x40
	private Coroutine m_updateStateCoroutine; // 0x48
	private Coroutine m_settleEnterSoundCoroutine; // 0x50
	private Coroutine m_newCompleteItemSoundCoroutine; // 0x58
	private Boolean m_hasInited; // 0x60
	private Action <onCloseClicked>k__BackingField; // 0x68
	private ILoadAsset <assetLoader>k__BackingField; // 0x70
	private UICharacterIllustLoader <illustLoader>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onCloseClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onCloseClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x10
	private static DelegateBridge __Hotfix0_set_assetLoader; // 0x18
	private static DelegateBridge __Hotfix0_get_illustLoader; // 0x20
	private static DelegateBridge __Hotfix0_set_illustLoader; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0_StartAnimation; // 0x38
	private static DelegateBridge __Hotfix0_StopAnimation; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0__UpdateStateCoroutine; // 0x50
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x58
	private static DelegateBridge __Hotfix0__PlayAudioCoroutine; // 0x60
	private static DelegateBridge __Hotfix0__OnScoreEnterAnimPlayFinish; // 0x68
	private static DelegateBridge __Hotfix0__OnScoreNewAnimPlayFinish; // 0x70
	private static DelegateBridge __Hotfix0__OnScoreResultAnimPlayFinish; // 0x78
	private static DelegateBridge __Hotfix0__OnNewCompleteAnimPlayFinish; // 0x80
	private static DelegateBridge __Hotfix0__OnResultEnterAnimPlayFinish; // 0x88
	private static DelegateBridge __Hotfix0__CloseView; // 0x90
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x98
	private static DelegateBridge __Hotfix0_EventOnPageClicked; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	private Action onCloseClicked { get; set; }
	private ILoadAsset assetLoader { get; set; }
	private UICharacterIllustLoader illustLoader { get; set; }

	// RVA: 0x2bd114c VA: 0x75951e914c
	private Action get_onCloseClicked() { }
	// RVA: 0x2bd11b4 VA: 0x75951e91b4
	public Void set_onCloseClicked(Action value) { }
	// RVA: 0x2bd1238 VA: 0x75951e9238
	private ILoadAsset get_assetLoader() { }
	// RVA: 0x2bd12a0 VA: 0x75951e92a0
	public Void set_assetLoader(ILoadAsset value) { }
	// RVA: 0x2bd1324 VA: 0x75951e9324
	private UICharacterIllustLoader get_illustLoader() { }
	// RVA: 0x2bd138c VA: 0x75951e938c
	public Void set_illustLoader(UICharacterIllustLoader value) { }
	// RVA: 0x2bd1410 VA: 0x75951e9410
	public Void Render(CrisisV2SettleViewModel viewModel) { }
	// RVA: 0x2bd18c4 VA: 0x75951e98c4
	public Void StartAnimation() { }
	// RVA: 0x2bd1a20 VA: 0x75951e9a20
	public Void StopAnimation() { }
	// RVA: 0x2bd15c0 VA: 0x75951e95c0
	private Void _InitIfNot() { }
	// RVA: 0x2bd1974 VA: 0x75951e9974
	private IEnumerator _UpdateStateCoroutine() { }
	// RVA: 0x2bd1b68 VA: 0x75951e9b68
	private static Void _PlayAnim(UIAnimationLocation anim, ref Tween tween, TweenCallback onComplete) { }
	// RVA: 0x2bd1d14 VA: 0x75951e9d14
	private static IEnumerator _PlayAudioCoroutine(Single delayTime, String signal, String subSignal) { }
	// RVA: 0x2bd1e24 VA: 0x75951e9e24
	private Void _OnScoreEnterAnimPlayFinish() { }
	// RVA: 0x2bd1eac VA: 0x75951e9eac
	private Void _OnScoreNewAnimPlayFinish() { }
	// RVA: 0x2bd1f18 VA: 0x75951e9f18
	private Void _OnScoreResultAnimPlayFinish() { }
	// RVA: 0x2bd1f84 VA: 0x75951e9f84
	private Void _OnNewCompleteAnimPlayFinish() { }
	// RVA: 0x2bd1ff0 VA: 0x75951e9ff0
	private Void _OnResultEnterAnimPlayFinish() { }
	// RVA: 0x2bd205c VA: 0x75951ea05c
	private Void _CloseView() { }
	// RVA: 0x2bd20f8 VA: 0x75951ea0f8
	private Void OnDestroy() { }
	// RVA: 0x2bd2160 VA: 0x75951ea160
	public Void EventOnPageClicked() { }
	// RVA: 0x2bd2390 VA: 0x75951ea390
	public Void .ctor() { }
}
```