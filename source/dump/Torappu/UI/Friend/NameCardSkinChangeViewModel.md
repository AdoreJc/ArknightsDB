# NameCardSkinChangeViewModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `NameCardV2SkinData selectedSkinData`

- `SkinState selectedSkinState`

- `ShowDetailOption showDetailOpt`

- `Int32 focusToIndex`

- `Int32 focusSkinListSeqNum`

- `Boolean isSkinChangeUnlocked`

- `NameCardSkinTmplChangeViewModel skinTmplChangeViewModel`

- `Boolean beShowSkinTmplPanel`

- `Int32 showSkinTmplSeqNum`


## Methods

- `Void LoadData()`

- `Void SelectSkin(String, Boolean)`

- `Void UpdateSkinList()`

- `Boolean TryToChangeSkinTmpl(String)`

- `Boolean TryHideChangeSkinTmpl()`

- `Boolean TrySelectSkinTmpl(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardSkinChangeViewModel : IHotfixable
{
	public List`1 itemViewModels; // 0x10
	public NameCardV2SkinData selectedSkinData; // 0x18
	public SkinState selectedSkinState; // 0x20
	public ShowDetailOption showDetailOpt; // 0x28
	public Int32 focusToIndex; // 0x2c
	public Int32 focusSkinListSeqNum; // 0x30
	public Boolean isSkinChangeUnlocked; // 0x34
	public NameCardSkinTmplChangeViewModel skinTmplChangeViewModel; // 0x38
	public Boolean beShowSkinTmplPanel; // 0x40
	public Int32 showSkinTmplSeqNum; // 0x44
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SelectSkin; // 0x8
	private static DelegateBridge __Hotfix0_UpdateSkinList; // 0x10
	private static DelegateBridge __Hotfix0_TryToChangeSkinTmpl; // 0x18
	private static DelegateBridge __Hotfix0_TryHideChangeSkinTmpl; // 0x20
	private static DelegateBridge __Hotfix0_TrySelectSkinTmpl; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x28be0e0 VA: 0x7594ed60e0
	public Void LoadData() { }
	// RVA: 0x28be800 VA: 0x7594ed6800
	public Void SelectSkin(String skinId, Boolean isOverridden) { }
	// RVA: 0x28be604 VA: 0x7594ed6604
	public Void UpdateSkinList() { }
	// RVA: 0x28be50c VA: 0x7594ed650c
	public Boolean TryToChangeSkinTmpl(String skinId) { }
	// RVA: 0x28be6e4 VA: 0x7594ed66e4
	public Boolean TryHideChangeSkinTmpl() { }
	// RVA: 0x28be760 VA: 0x7594ed6760
	public Boolean TrySelectSkinTmpl(Int32 skinTmpl) { }
	// RVA: 0x28bf3d4 VA: 0x7594ed73d4
	public Void .ctor() { }
}
```