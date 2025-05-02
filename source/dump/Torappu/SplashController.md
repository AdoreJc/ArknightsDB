# SplashController

**Namespace:** `Torappu`


## Fields

- `Single _initialFadeTime`

- `Single _regularFadeTime`

- `Single _showTime`

- `Image _blackCoverImage`

- `PerformanceTest _performanceTest`

- `GameObject _warningDialog`

- `Text _textResourceLoading`

- `Text _textConnectUs`

- `Text _textConfirm`

- `Sequence m_tween`

- `SwitchSceneTrigger m_sceneTrigger`


## Methods

- `Void Start()`

- `Void Update()`

- `Void _ShowInitLicense()`

- `Void _OnTweenFinished()`

- `Void _SwitchToInitScene()`

- `Boolean _CheckIfResValid()`

- `Void _HandlePerformanceTest()`

- `Void _ShowResourceLoadFail()`

- `Void _ShowSplashImage(Int32)`

- `Void _PerformanceTestFinish()`

- `Void _ExitGame()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SplashController : MonoBehaviour
{
	private Single _initialFadeTime; // 0x18
	private Single _regularFadeTime; // 0x1c
	private Single _showTime; // 0x20
	private Image _blackCoverImage; // 0x28
	private GameObject[] _gameObjectSplashImages; // 0x30
	private PerformanceTest _performanceTest; // 0x38
	private GameObject _warningDialog; // 0x40
	private Text _textResourceLoading; // 0x48
	private Text _textConnectUs; // 0x50
	private Text _textConfirm; // 0x58
	private Sequence m_tween; // 0x60
	private SwitchSceneTrigger m_sceneTrigger; // 0x68


	// RVA: 0x3106cfc VA: 0x759571ecfc
	private Void Start() { }
	// RVA: 0x3107160 VA: 0x759571f160
	private Void Update() { }
	// RVA: 0x31070c8 VA: 0x759571f0c8
	private Void _ShowInitLicense() { }
	// RVA: 0x3107228 VA: 0x759571f228
	private Void _OnTweenFinished() { }
	// RVA: 0x310724c VA: 0x759571f24c
	private Void _SwitchToInitScene() { }
	// RVA: 0x31072d0 VA: 0x759571f2d0
	private Boolean _CheckIfResValid() { }
	// RVA: 0x3107538 VA: 0x759571f538
	private Void _HandlePerformanceTest() { }
	// RVA: 0x3107518 VA: 0x759571f518
	private Void _ShowResourceLoadFail() { }
	// RVA: 0x310761c VA: 0x759571f61c
	private Void _ShowSplashImage(Int32 index) { }
	// RVA: 0x31076c8 VA: 0x759571f6c8
	private Void _PerformanceTestFinish() { }
	// RVA: 0x3107758 VA: 0x759571f758
	public Void _ExitGame() { }
	// RVA: 0x3107760 VA: 0x759571f760
	public Void .ctor() { }
}
```