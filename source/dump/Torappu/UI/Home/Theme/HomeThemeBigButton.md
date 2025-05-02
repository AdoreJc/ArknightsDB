# HomeThemeBigButton

**Namespace:** `Torappu.UI.Home.Theme`


## Fields

- `UIColorGraphic _btnGraphic`

- `Image _mainImg`

- `Image _bgImg`

- `PrefabDisplay _bgPrefab`


## Methods

- `Void _ApplyImage(ImageData, Image, HomeTheme)`

- `Void HideOrShowMainImg()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Theme
public class HomeThemeBigButton : HomeThemeUIElem`1
{
	private UIColorGraphic _btnGraphic; // 0x30
	private Image _mainImg; // 0x38
	private Image _bgImg; // 0x40
	private PrefabDisplay _bgPrefab; // 0x48
	private static DelegateBridge __Hotfix0_OnUIApply; // 0x0
	private static DelegateBridge __Hotfix0_OnGenData; // 0x8
	private static DelegateBridge __Hotfix0__ApplyImage; // 0x10
	private static DelegateBridge __Hotfix0_OnFillUIData; // 0x18
	private static DelegateBridge __Hotfix0_OnClearRef; // 0x20
	private static DelegateBridge __Hotfix0_HideOrShowMainImg; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x284a798 VA: 0x7594e62798
	protected override Void OnUIApply(HomeThemeBigButtonData data, HomeTheme theme) { }
	// RVA: 0x284add4 VA: 0x7594e62dd4
	public override Void OnGenData() { }
	// RVA: 0x284ab84 VA: 0x7594e62b84
	private Void _ApplyImage(ImageData data, Image image, HomeTheme theme) { }
	// RVA: 0x284ae68 VA: 0x7594e62e68
	protected override Void OnFillUIData(HomeThemeBigButtonData data, AssetPathConvertor pathConvertor) { }
	// RVA: 0x284b0e8 VA: 0x7594e630e8
	protected override Void OnClearRef() { }
	// RVA: 0x284b228 VA: 0x7594e63228
	public Void HideOrShowMainImg() { }
	// RVA: 0x284b314 VA: 0x7594e63314
	public Void .ctor() { }
}
```