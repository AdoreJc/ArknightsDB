# UIBattleLegionIntermissionTipsPanel

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `GameObject _objRestPart`

- `CanvasGroup _canvasRestSlider`

- `CanvasGroup _canvasRestLine`

- `CanvasGroup _canvasRestTips`

- `RectTransform _transRestLine`

- `Slider _sliderResetTime`

- `Single m_restSliderChangeTime`

- `IntermissionPanelRestShowTween m_RestTween`

- `Boolean m_hasInited`

- `Single m_prepareTimeForNextWave`

- `Single m_maxPrepareTime`

- `Boolean m_preparingForNextWave`


## Methods

- `Void UpdateGameInfo()`

- `Void OnCurWaveWillFinish(Single, Int32)`

- `Void _Show()`

- `Void _InitIfNot()`

- `Void _PlayRestTipsTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class UIBattleLegionIntermissionTipsPanel : MonoBehaviour, IHotfixable
{
	private GameObject _objRestPart; // 0x18
	private CanvasGroup _canvasRestSlider; // 0x20
	private CanvasGroup _canvasRestLine; // 0x28
	private CanvasGroup _canvasRestTips; // 0x30
	private RectTransform _transRestLine; // 0x38
	private Slider _sliderResetTime; // 0x40
	private Single m_restSliderChangeTime; // 0x48
	private IntermissionPanelRestShowTween m_RestTween; // 0x50
	private Boolean m_hasInited; // 0x58
	private Single m_prepareTimeForNextWave; // 0x5c
	private Single m_maxPrepareTime; // 0x60
	private Boolean m_preparingForNextWave; // 0x64
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x0
	private static DelegateBridge __Hotfix0_OnCurWaveWillFinish; // 0x8
	private static DelegateBridge __Hotfix0__Show; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlayRestTipsTween; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1db77c4 VA: 0x75943cf7c4
	public Void UpdateGameInfo() { }
	// RVA: 0x1db7960 VA: 0x75943cf960
	public Void OnCurWaveWillFinish(Single showTime, Int32 goldForWaveEnd) { }
	// RVA: 0x1db78e0 VA: 0x75943cf8e0
	private Void _Show() { }
	// RVA: 0x1db7a38 VA: 0x75943cfa38
	private Void _InitIfNot() { }
	// RVA: 0x1db7af4 VA: 0x75943cfaf4
	private Void _PlayRestTipsTween() { }
	// RVA: 0x1db8268 VA: 0x75943d0268
	public Void .ctor() { }
}
```