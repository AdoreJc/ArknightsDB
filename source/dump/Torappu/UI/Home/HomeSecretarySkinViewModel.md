# HomeSecretarySkinViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `SkinSelectViewModel selectViewModel`

- `Boolean <showCanUsePart>k__BackingField`

- `Boolean <showGotoShopPart>k__BackingField`

- `Boolean <showJustForShowPart>k__BackingField`


## Properties

- `Boolean showCanUsePart`

- `Boolean showGotoShopPart`

- `Boolean showJustForShowPart`


## Methods

- `Boolean get_showCanUsePart()`

- `Void set_showCanUsePart(Boolean)`

- `Boolean get_showGotoShopPart()`

- `Void set_showGotoShopPart(Boolean)`

- `Boolean get_showJustForShowPart()`

- `Void set_showJustForShowPart(Boolean)`

- `Void InitData(Int32, CharSkinData, Boolean)`

- `Void InitData(Int32, SkinShopViewModel, Boolean)`

- `Void _InitViewStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretarySkinViewModel : IHotfixable
{
	public SkinSelectViewModel selectViewModel; // 0x10
	private Boolean <showCanUsePart>k__BackingField; // 0x18
	private Boolean <showGotoShopPart>k__BackingField; // 0x19
	private Boolean <showJustForShowPart>k__BackingField; // 0x1a
	private static DelegateBridge __Hotfix0_get_showCanUsePart; // 0x0
	private static DelegateBridge __Hotfix0_set_showCanUsePart; // 0x8
	private static DelegateBridge __Hotfix0_get_showGotoShopPart; // 0x10
	private static DelegateBridge __Hotfix0_set_showGotoShopPart; // 0x18
	private static DelegateBridge __Hotfix0_get_showJustForShowPart; // 0x20
	private static DelegateBridge __Hotfix0_set_showJustForShowPart; // 0x28
	private static DelegateBridge __Hotfix0_InitData; // 0x30
	private static DelegateBridge __Hotfix1_InitData; // 0x38
	private static DelegateBridge __Hotfix0__InitViewStatus; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean showCanUsePart { get; set; }
	public Boolean showGotoShopPart { get; set; }
	public Boolean showJustForShowPart { get; set; }

	// RVA: 0x2819790 VA: 0x7594e31790
	public Boolean get_showCanUsePart() { }
	// RVA: 0x28197f8 VA: 0x7594e317f8
	private Void set_showCanUsePart(Boolean value) { }
	// RVA: 0x2819878 VA: 0x7594e31878
	public Boolean get_showGotoShopPart() { }
	// RVA: 0x28198e0 VA: 0x7594e318e0
	private Void set_showGotoShopPart(Boolean value) { }
	// RVA: 0x2819960 VA: 0x7594e31960
	public Boolean get_showJustForShowPart() { }
	// RVA: 0x28199c8 VA: 0x7594e319c8
	private Void set_showJustForShowPart(Boolean value) { }
	// RVA: 0x2819a48 VA: 0x7594e31a48
	public Void InitData(Int32 index, CharSkinData importData, Boolean secretaryFlag) { }
	// RVA: 0x2819c18 VA: 0x7594e31c18
	public Void InitData(Int32 index, SkinShopViewModel shopData, Boolean secretaryFlag) { }
	// RVA: 0x2819b44 VA: 0x7594e31b44
	private Void _InitViewStatus() { }
	// RVA: 0x2819d14 VA: 0x7594e31d14
	public Void .ctor() { }
}
```