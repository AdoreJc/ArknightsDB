# DIYFurnitureTitleView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Text _titleText`

- `DIYFurnitureRowView _rowView`


## Properties

- `String text`


## Methods

- `String get_text()`

- `Void set_text(String)`

- `Void OnInit(List`1, DIYViewListThemeState)`

- `Vector2 GetTextRect()`

- `TextGenerationSettings GetTextGenerationSettings(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurnitureTitleView : DIYFurnitureVerticalListElementView
{
	private Text _titleText; // 0x20
	private DIYFurnitureRowView _rowView; // 0x28
	public Func`2 furnitureSelected; // 0x30
	public Func`2 infoButtonPressed; // 0x38
	private static DelegateBridge __Hotfix0_get_text; // 0x0
	private static DelegateBridge __Hotfix0_set_text; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_GetTextRect; // 0x18
	private static DelegateBridge __Hotfix0_GetTextGenerationSettings; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String text { get; set; }

	// RVA: 0x381f868 VA: 0x7595e37868
	public String get_text() { }
	// RVA: 0x381eea4 VA: 0x7595e36ea4
	public Void set_text(String value) { }
	// RVA: 0x381ef38 VA: 0x7595e36f38
	public Void OnInit(List`1 itemViewDatas, DIYViewListThemeState themeState) { }
	// RVA: 0x381f8e4 VA: 0x7595e378e4
	public Vector2 GetTextRect() { }
	// RVA: 0x381f980 VA: 0x7595e37980
	public TextGenerationSettings GetTextGenerationSettings(Vector2 extents) { }
	// RVA: 0x381fa48 VA: 0x7595e37a48
	public Void .ctor() { }
}
```