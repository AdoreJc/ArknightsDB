# ShopRecommendTemplateNormalFurnViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Int64 m_showStartTs`

- `Int64 m_showEndTs`

- `String m_furnSetName`

- `String m_desc`

- `String m_backColor`

- `String m_textColor`

- `Boolean m_isNew`

- `Boolean m_isFullPack`

- `Int32 m_count`

- `String m_actName`


## Properties

- `Int64 showStartTs`

- `Int64 showEndTs`

- `String furnSetName`

- `String desc`

- `String backColor`

- `String textColor`

- `Boolean isNew`

- `Boolean isFullPack`

- `Int32 count`

- `String actName`


## Methods

- `Int64 get_showStartTs()`

- `Int64 get_showEndTs()`

- `String get_furnSetName()`

- `String get_desc()`

- `String get_backColor()`

- `String get_textColor()`

- `Boolean get_isNew()`

- `Boolean get_isFullPack()`

- `Int32 get_count()`

- `String get_actName()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopRecommendTemplateNormalFurnViewModel : ShopRecommendTemplateViewModelBase, IHotfixable
{
	protected Int64 m_showStartTs; // 0x18
	protected Int64 m_showEndTs; // 0x20
	private String m_furnSetName; // 0x28
	private String m_desc; // 0x30
	private String m_backColor; // 0x38
	private String m_textColor; // 0x40
	private Boolean m_isNew; // 0x48
	private Boolean m_isFullPack; // 0x49
	private Int32 m_count; // 0x4c
	private String m_actName; // 0x50
	private static DelegateBridge __Hotfix0_get_showStartTs; // 0x0
	private static DelegateBridge __Hotfix0_get_showEndTs; // 0x8
	private static DelegateBridge __Hotfix0_get_furnSetName; // 0x10
	private static DelegateBridge __Hotfix0_get_desc; // 0x18
	private static DelegateBridge __Hotfix0_get_backColor; // 0x20
	private static DelegateBridge __Hotfix0_get_textColor; // 0x28
	private static DelegateBridge __Hotfix0_get_isNew; // 0x30
	private static DelegateBridge __Hotfix0_get_isFullPack; // 0x38
	private static DelegateBridge __Hotfix0_get_count; // 0x40
	private static DelegateBridge __Hotfix0_get_actName; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Int64 showStartTs { get; }
	public Int64 showEndTs { get; }
	public String furnSetName { get; }
	public String desc { get; }
	public String backColor { get; }
	public String textColor { get; }
	public Boolean isNew { get; }
	public Boolean isFullPack { get; }
	public Int32 count { get; }
	public String actName { get; }

	// RVA: 0x245ee28 VA: 0x7594a76e28
	public Int64 get_showStartTs() { }
	// RVA: 0x245ee90 VA: 0x7594a76e90
	public Int64 get_showEndTs() { }
	// RVA: 0x245efc8 VA: 0x7594a76fc8
	public String get_furnSetName() { }
	// RVA: 0x245f030 VA: 0x7594a77030
	public String get_desc() { }
	// RVA: 0x245f168 VA: 0x7594a77168
	public String get_backColor() { }
	// RVA: 0x245f1d0 VA: 0x7594a771d0
	public String get_textColor() { }
	// RVA: 0x245ef60 VA: 0x7594a76f60
	public Boolean get_isNew() { }
	// RVA: 0x245eef8 VA: 0x7594a76ef8
	public Boolean get_isFullPack() { }
	// RVA: 0x245f098 VA: 0x7594a77098
	public Int32 get_count() { }
	// RVA: 0x245f100 VA: 0x7594a77100
	public String get_actName() { }
	// RVA: 0x245f344 VA: 0x7594a77344
	public override Void LoadData(ShopRecommendItem recommendItem) { }
	// RVA: 0x245f518 VA: 0x7594a77518
	public Void .ctor() { }
}
```