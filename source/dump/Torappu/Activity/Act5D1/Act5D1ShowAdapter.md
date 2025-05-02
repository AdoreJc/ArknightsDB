# Act5D1ShowAdapter

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Boolean canUnlockFlag`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1ShowAdapter : SimpleLayoutAdapter, IHotfixable
{
	public List`1 runeShowList; // 0x20
	public Boolean canUnlockFlag; // 0x28
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x31ca514 VA: 0x75957e2514
	public override Int32 get_count() { }
	// RVA: 0x31ca594 VA: 0x75957e2594
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x31ca76c VA: 0x75957e276c
	public Void .ctor() { }
}
```