# HandBookGroupForceEditAdapter

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `UIStringEvent onClick`

- `UIStringEvent onFocusView`

- `UIStringEvent onSaveFocusView`

- `UIStringEvent onDeleteForce`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookGroupForceEditAdapter : SimpleLayoutAdapter
{
	public UIStringEvent onClick; // 0x20
	public UIStringEvent onFocusView; // 0x28
	public UIStringEvent onSaveFocusView; // 0x30
	public UIStringEvent onDeleteForce; // 0x38
	public List`1 forceData; // 0x40
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x2ec4ec4 VA: 0x75954dcec4
	public override Int32 get_count() { }
	// RVA: 0x2ec4f44 VA: 0x75954dcf44
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2ec19c0 VA: 0x75954d99c0
	public Void .ctor() { }
}
```