# ItemRepoItemDetailState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoItemDetailStateBean _stateBean`

- `ItemRepoItemDetailLeftView _leftView`

- `ItemRepoDropInfoView _dropInfoView`

- `ItemRepoItemDetailRightDescView _descView`

- `Transform _dropInfoContainer`

- `ItemRepoItemDetailPackContentInfoPlugin _packContentInfoPlugin`

- `Boolean m_dropInfoInitFlag`

- `ItemRepoDropInfoView m_dropItemInfo`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateItemDropInfo(UIItemViewModel, UIItemDescViewModel)`

- `Void Render(UIItemViewModel)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoItemDetailState : PopupFloatState
{
	protected ItemRepoItemDetailStateBean _stateBean; // 0x70
	private ItemRepoItemDetailLeftView _leftView; // 0x78
	private ItemRepoDropInfoView _dropInfoView; // 0x80
	private ItemRepoItemDetailRightDescView _descView; // 0x88
	private Transform _dropInfoContainer; // 0x90
	private ItemRepoItemDetailPackContentInfoPlugin _packContentInfoPlugin; // 0x98
	private Boolean m_dropInfoInitFlag; // 0xa0
	private ItemRepoDropInfoView m_dropItemInfo; // 0xa8
	private Boolean m_isInited; // 0xb0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__UpdateItemDropInfo; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2d26ed4 VA: 0x759533eed4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d29d80 VA: 0x7595341d80
	private Void _InitIfNot() { }
	// RVA: 0x2d2574c VA: 0x759533d74c
	protected override Void OnEnter() { }
	// RVA: 0x2d29ffc VA: 0x7595341ffc
	protected override Void OnResume() { }
	// RVA: 0x2d2a09c VA: 0x759534209c
	private Void _UpdateItemDropInfo(UIItemViewModel itemModel, UIItemDescViewModel descModel) { }
	// RVA: 0x2d29ecc VA: 0x7595341ecc
	public Void Render(UIItemViewModel itemViewModel) { }
	// RVA: 0x2d26ad0 VA: 0x759533ead0
	public Void .ctor() { }
	// RVA: 0x2d2a6c4 VA: 0x75953426c4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d2a6cc VA: 0x75953426cc
	private Void <>xLuaBaseProxy_OnResume() { }
}
```