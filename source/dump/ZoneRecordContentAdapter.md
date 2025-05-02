# ZoneRecordContentAdapter

**Namespace:** ` `


## Fields

- `String selectedRecordId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ZoneRecordContentAdapter : SimpleLayoutAdapter, IHotfixable
{
	public List`1 recordList; // 0x20
	public Action`1 clickAction; // 0x28
	public String selectedRecordId; // 0x30
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x2fdd870 VA: 0x75955f5870
	public override Int32 get_count() { }
	// RVA: 0x2fdd8f0 VA: 0x75955f58f0
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2fdcd14 VA: 0x75955f4d14
	public Void .ctor() { }
}
```