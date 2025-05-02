# DIYFurnitureVirtualView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `GameObject elementPrefab`

- `DIYItemViewData itemData`

- `Int32 index`

- `ElementType elementType`


## Methods

- `Void UpdateItemView(DIYItemViewData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurnitureVirtualView : VirtualView`1
{
	public GameObject elementPrefab; // 0x20
	public DIYItemViewData itemData; // 0x28
	public Int32 index; // 0x30
	public ElementType elementType; // 0x34
	public Func`2 OnSelected; // 0x38
	public Func`2 OnInfo; // 0x40
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x0
	private static DelegateBridge __Hotfix0_GetPreferSize; // 0x8
	private static DelegateBridge __Hotfix0_UpdateItemView; // 0x10
	private static DelegateBridge __Hotfix0_OnViewAttached; // 0x18
	private static DelegateBridge __Hotfix0_OnViewDetached; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x382b6dc VA: 0x7595e436dc
	public override GameObject GetPrefab() { }
	// RVA: 0x382b744 VA: 0x7595e43744
	public override Single GetPreferSize() { }
	// RVA: 0x382b7f8 VA: 0x7595e437f8
	public Void UpdateItemView(DIYItemViewData data) { }
	// RVA: 0x382b910 VA: 0x7595e43910
	protected override Void OnViewAttached() { }
	// RVA: 0x382ba38 VA: 0x7595e43a38
	protected override Void OnViewDetached() { }
	// RVA: 0x382ba9c VA: 0x7595e43a9c
	public Void .ctor() { }
}
```