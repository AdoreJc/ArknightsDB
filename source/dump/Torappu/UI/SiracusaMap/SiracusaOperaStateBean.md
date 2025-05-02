# SiracusaOperaStateBean

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Int32 selectIndex`

- `Int32 totalSelect`

- `Int32 remainSelect`

- `String selectId`

- `Boolean isAllRelease`


## Methods

- `Void InitData()`

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaStateBean : IStateBean, IHotfixable
{
	public List`1 viewModelList; // 0x10
	public Int32 selectIndex; // 0x18
	public Int32 totalSelect; // 0x1c
	public Int32 remainSelect; // 0x20
	public String selectId; // 0x28
	public Boolean isAllRelease; // 0x30
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x23f9668 VA: 0x7594a11668
	public Void InitData() { }
	// RVA: 0x23f9b8c VA: 0x7594a11b8c
	public Void RefreshPlayerData() { }
	// RVA: 0x23fa044 VA: 0x7594a12044
	public Void .ctor() { }
}
```