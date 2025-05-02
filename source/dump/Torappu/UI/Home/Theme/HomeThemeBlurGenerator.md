# HomeThemeBlurGenerator

**Namespace:** `Torappu.UI.Home.Theme`


## Fields

- `Int32 _blurLevel`

- `HomeThemeBlurHolder m_blurGenHolder`

- `HomeTheme m_cacheTheme`


## Methods

- `Void _ApplyGeneratorParam(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Theme
public class HomeThemeBlurGenerator : HomeThemeElemBase`1
{
	private Int32 _blurLevel; // 0x24
	private HomeThemeBlurHolder m_blurGenHolder; // 0x28
	private HomeTheme m_cacheTheme; // 0x30
	private static DelegateBridge __Hotfix0_OnApply; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyEmpty; // 0x8
	private static DelegateBridge __Hotfix0__ApplyGeneratorParam; // 0x10
	private static DelegateBridge __Hotfix0_OnFillData; // 0x18
	private static DelegateBridge __Hotfix0_OnClearRef; // 0x20
	private static DelegateBridge __Hotfix0_ChangeParam; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x284b450 VA: 0x7594e63450
	protected override Void OnApply(HomeThemeBlurGeneratorData data, HomeTheme theme) { }
	// RVA: 0x284b74c VA: 0x7594e6374c
	protected override Void OnApplyEmpty() { }
	// RVA: 0x284b4f4 VA: 0x7594e634f4
	private Void _ApplyGeneratorParam(Int32 blurLevel, Int32 downSample) { }
	// RVA: 0x284b948 VA: 0x7594e63948
	protected override Void OnFillData(HomeThemeBlurGeneratorData data, AssetPathConvertor pathConvertor) { }
	// RVA: 0x284b9d8 VA: 0x7594e639d8
	protected override Void OnClearRef() { }
	// RVA: 0x284ba58 VA: 0x7594e63a58
	public static Void ChangeParam(Int32 blurLevel, Int32 downSample) { }
	// RVA: 0x284bb74 VA: 0x7594e63b74
	public Void .ctor() { }
}
```