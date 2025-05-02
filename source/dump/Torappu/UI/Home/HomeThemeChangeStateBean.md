# HomeThemeChangeStateBean

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeThemeChangeViewProperty themeChangeProperty`

- `String presetInstId`

- `String presetThemeId`

- `String presetBackgroundId`

- `Int32 m_routedSequenceNum`


## Methods

- `Void ApplySelectTheme(String)`

- `Void ResortList(Boolean)`

- `Void _ConsumeNew(String)`

- `Void InitData(String)`

- `Void ChangeHideState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeThemeChangeStateBean : IStateBean, IHotfixable
{
	public HomeThemeChangeViewProperty themeChangeProperty; // 0x10
	public String presetInstId; // 0x18
	public String presetThemeId; // 0x20
	public String presetBackgroundId; // 0x28
	private Int32 m_routedSequenceNum; // 0x30
	private static DelegateBridge __Hotfix0_ApplySelectTheme; // 0x0
	private static DelegateBridge __Hotfix0_ResortList; // 0x8
	private static DelegateBridge __Hotfix0__CompareUpdateTimeAscend; // 0x10
	private static DelegateBridge __Hotfix0__CompareUpdateTimeDescend; // 0x18
	private static DelegateBridge __Hotfix0__ConsumeNew; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x28
	private static DelegateBridge __Hotfix0_ChangeHideState; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2819d84 VA: 0x7594e31d84
	public Void ApplySelectTheme(String selectTheme) { }
	// RVA: 0x2819fb4 VA: 0x7594e31fb4
	public Void ResortList(Boolean ascend) { }
	// RVA: 0x281a144 VA: 0x7594e32144
	private static Int32 _CompareUpdateTimeAscend(HomeThemeItemModel left, HomeThemeItemModel right) { }
	// RVA: 0x281a240 VA: 0x7594e32240
	private static Int32 _CompareUpdateTimeDescend(HomeThemeItemModel left, HomeThemeItemModel right) { }
	// RVA: 0x2819f30 VA: 0x7594e31f30
	private Void _ConsumeNew(String bgId) { }
	// RVA: 0x281a348 VA: 0x7594e32348
	public Void InitData(String routedHomeThemeId) { }
	// RVA: 0x281a8e4 VA: 0x7594e328e4
	public Void ChangeHideState() { }
	// RVA: 0x281a998 VA: 0x7594e32998
	public Void .ctor() { }
}
```