# APItemAdapter

**Namespace:** ` `


## Fields

- `Int32 selectIndex`

- `Single scaleFactor`


## Methods

- `Void InitSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class APItemAdapter : SimpleLayoutAdapter
{
	public List`1 itemInfo; // 0x20
	public Int32 selectIndex; // 0x28
	public Single scaleFactor; // 0x2c
	public Action`1 clickEvent; // 0x30
	public Action`1 refreshEvent; // 0x38
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_InitSelect; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 count { get; }

	// RVA: 0x2f8bbb4 VA: 0x75955a3bb4
	public override Int32 get_count() { }
	// RVA: 0x2f8b958 VA: 0x75955a3958
	public Void InitSelect() { }
	// RVA: 0x2f8bc38 VA: 0x75955a3c38
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2f8b8e8 VA: 0x75955a38e8
	public Void .ctor() { }
}
```