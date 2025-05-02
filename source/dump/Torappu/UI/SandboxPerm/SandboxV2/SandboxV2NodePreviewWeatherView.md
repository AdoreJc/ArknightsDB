# SandboxV2NodePreviewWeatherView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _weatherClassImage`

- `Image _weatherIcon`

- `Text _weatherType`

- `Text _weatherName`

- `Button _btnWeatherPreview`

- `SandboxV2NodePreviewWeatherFloatPanel _weatherFloatPanel`

- `UIPageFinder m_pageFinder`

- `SandboxV2WeatherData m_cachedWeatherData`


## Methods

- `Void Render(SandboxV2DungeonNodeViewModel)`

- `Void Render(String, SandboxV2WeatherData)`

- `Void CloseWeatherDetail()`

- `Void OnBtnWeatherDetailClicked()`

- `GameObject TutorialOnly_GetStartBattleGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodePreviewWeatherView : MonoBehaviour, IHotfixable
{
	private Image _weatherClassImage; // 0x18
	private Image _weatherIcon; // 0x20
	private Text _weatherType; // 0x28
	private Text _weatherName; // 0x30
	private Button _btnWeatherPreview; // 0x38
	private SandboxV2NodePreviewWeatherFloatPanel _weatherFloatPanel; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private SandboxV2WeatherData m_cachedWeatherData; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix1_Render; // 0x8
	private static DelegateBridge __Hotfix0_CloseWeatherDetail; // 0x10
	private static DelegateBridge __Hotfix0_OnBtnWeatherDetailClicked; // 0x18
	private static DelegateBridge __Hotfix0_TutorialOnly_GetStartBattleGo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x256f1fc VA: 0x7594b871fc
	public Void Render(SandboxV2DungeonNodeViewModel nodeViewModel) { }
	// RVA: 0x25702b8 VA: 0x7594b882b8
	public Void Render(String topicId, SandboxV2WeatherData weatherData) { }
	// RVA: 0x256f310 VA: 0x7594b87310
	public Void CloseWeatherDetail() { }
	// RVA: 0x2570460 VA: 0x7594b88460
	public Void OnBtnWeatherDetailClicked() { }
	// RVA: 0x256fb74 VA: 0x7594b87b74
	public GameObject TutorialOnly_GetStartBattleGo() { }
	// RVA: 0x25704fc VA: 0x7594b884fc
	public Void .ctor() { }
}
```