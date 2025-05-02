# ShopRecommendTemplateNormalSkinViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Int64 m_showStartTs`

- `Int64 m_showEndTs`

- `String m_seriesName`

- `String m_brandIconId`

- `String m_colorBack`

- `String m_colorText`

- `String m_text`


## Properties

- `Int64 showStartTs`

- `Int64 showEndTs`

- `String seriesName`

- `String brandIconId`

- `String colorBack`

- `String colorText`

- `String text`


## Methods

- `Int64 get_showStartTs()`

- `Int64 get_showEndTs()`

- `String get_seriesName()`

- `String get_brandIconId()`

- `String get_colorBack()`

- `String get_colorText()`

- `String get_text()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopRecommendTemplateNormalSkinViewModel : ShopRecommendTemplateViewModelBase, IHotfixable
{
	protected Int64 m_showStartTs; // 0x18
	protected Int64 m_showEndTs; // 0x20
	private String m_seriesName; // 0x28
	private String m_brandIconId; // 0x30
	private String m_colorBack; // 0x38
	private String m_colorText; // 0x40
	private String m_text; // 0x48
	private List`1 m_skinNames; // 0x50
	private static DelegateBridge __Hotfix0_get_showStartTs; // 0x0
	private static DelegateBridge __Hotfix0_get_showEndTs; // 0x8
	private static DelegateBridge __Hotfix0_get_seriesName; // 0x10
	private static DelegateBridge __Hotfix0_get_brandIconId; // 0x18
	private static DelegateBridge __Hotfix0_get_colorBack; // 0x20
	private static DelegateBridge __Hotfix0_get_colorText; // 0x28
	private static DelegateBridge __Hotfix0_get_text; // 0x30
	private static DelegateBridge __Hotfix0_get_skinNames; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int64 showStartTs { get; }
	public Int64 showEndTs { get; }
	public String seriesName { get; }
	public String brandIconId { get; }
	public String colorBack { get; }
	public String colorText { get; }
	public String text { get; }
	public List`1 skinNames { get; }

	// RVA: 0x246079c VA: 0x7594a7879c
	public Int64 get_showStartTs() { }
	// RVA: 0x2460804 VA: 0x7594a78804
	public Int64 get_showEndTs() { }
	// RVA: 0x246093c VA: 0x7594a7893c
	public String get_seriesName() { }
	// RVA: 0x24608d4 VA: 0x7594a788d4
	public String get_brandIconId() { }
	// RVA: 0x2460bac VA: 0x7594a78bac
	public String get_colorBack() { }
	// RVA: 0x2460c14 VA: 0x7594a78c14
	public String get_colorText() { }
	// RVA: 0x246086c VA: 0x7594a7886c
	public String get_text() { }
	// RVA: 0x24609a4 VA: 0x7594a789a4
	public List`1 get_skinNames() { }
	// RVA: 0x2460d0c VA: 0x7594a78d0c
	public override Void LoadData(ShopRecommendItem recommendItem) { }
	// RVA: 0x2461088 VA: 0x7594a79088
	public Void .ctor() { }
}
```