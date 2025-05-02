# NameCardSkinChangeStateBean

**Namespace:** `Torappu.UI.Friend`


## Fields

- `NameCardV2Property nameCardProperty`

- `NameCardSkinChangeProperty skinChangeProperty`


## Properties

- `String selectedSkinId`


## Methods

- `String get_selectedSkinId()`

- `Void LoadData(String)`

- `Void SelectSkin(String)`

- `Boolean CheckNeedChangeSkinRequest()`

- `Void ToChangeSkinTmpl(String)`

- `Void UpdateSkinList()`

- `Void HideChangeSkinTmpl()`

- `Void SelectSkinTmpl(Int32)`

- `Void _LoadModels(String, NameCardSkinChangeViewModel, NameCardV2ViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardSkinChangeStateBean : IStateBean, IHotfixable
{
	public NameCardV2Property nameCardProperty; // 0x10
	public NameCardSkinChangeProperty skinChangeProperty; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedSkinId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SelectSkin; // 0x10
	private static DelegateBridge __Hotfix0_CheckNeedChangeSkinRequest; // 0x18
	private static DelegateBridge __Hotfix0_ToChangeSkinTmpl; // 0x20
	private static DelegateBridge __Hotfix0_UpdateSkinList; // 0x28
	private static DelegateBridge __Hotfix0_HideChangeSkinTmpl; // 0x30
	private static DelegateBridge __Hotfix0_SelectSkinTmpl; // 0x38
	private static DelegateBridge __Hotfix0__LoadModels; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String selectedSkinId { get; }

	// RVA: 0x28b8e30 VA: 0x7594ed0e30
	public String get_selectedSkinId() { }
	// RVA: 0x28b8ba8 VA: 0x7594ed0ba8
	public Void LoadData(String overrideSkinId) { }
	// RVA: 0x28b8ee4 VA: 0x7594ed0ee4
	public Void SelectSkin(String selectedId) { }
	// RVA: 0x28b98bc VA: 0x7594ed18bc
	public Boolean CheckNeedChangeSkinRequest() { }
	// RVA: 0x28b905c VA: 0x7594ed105c
	public Void ToChangeSkinTmpl(String skinId) { }
	// RVA: 0x28b9e38 VA: 0x7594ed1e38
	public Void UpdateSkinList() { }
	// RVA: 0x28b91a0 VA: 0x7594ed11a0
	public Void HideChangeSkinTmpl() { }
	// RVA: 0x28b92e0 VA: 0x7594ed12e0
	public Void SelectSkinTmpl(Int32 skinTmpl) { }
	// RVA: 0x28be3f4 VA: 0x7594ed63f4
	private Void _LoadModels(String selectedId, NameCardSkinChangeViewModel changeModel, NameCardV2ViewModel cardModel, Boolean isOverridden) { }
	// RVA: 0x28b9cd8 VA: 0x7594ed1cd8
	public Void .ctor() { }
}
```