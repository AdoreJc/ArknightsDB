# SandboxV2NodePreviewWeatherFloatPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _detailAlphaHandler`

- `RectTransform _detailPositionHandler`

- `Vector2 _detailShowPos`

- `Vector2 _detailHidePos`

- `Text _weatherEffect`

- `Text _weatherDesc`

- `Boolean m_inited`

- `UISwitchTween m_detailShowTween`


## Methods

- `Void _InitIfNot()`

- `Void Render(SandboxV2WeatherData)`

- `Void _TutorialOnly_TryRaiseAVGSignal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodePreviewWeatherFloatPanel : SandboxV2FloatPanel
{
	private CanvasGroup _detailAlphaHandler; // 0x30
	private RectTransform _detailPositionHandler; // 0x38
	private Vector2 _detailShowPos; // 0x40
	private Vector2 _detailHidePos; // 0x48
	private Text _weatherEffect; // 0x50
	private Text _weatherDesc; // 0x58
	private Boolean m_inited; // 0x60
	private UISwitchTween m_detailShowTween; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_SetShowStatus; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRaiseAVGSignal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x256fe04 VA: 0x7594b87e04
	private Void _InitIfNot() { }
	// RVA: 0x256ffc0 VA: 0x7594b87fc0
	protected override Void SetShowStatus(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2570070 VA: 0x7594b88070
	public Void Render(SandboxV2WeatherData weatherData) { }
	// RVA: 0x2570124 VA: 0x7594b88124
	public Void _TutorialOnly_TryRaiseAVGSignal() { }
	// RVA: 0x2570248 VA: 0x7594b88248
	public Void .ctor() { }
}
```