# MainCheckResNode

**Namespace:** ` `


## Methods

- `Void _DeleteUnusedFiles(PersistentResInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MainCheckResNode : CheckResNode
{
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_GetCheckType; // 0x8
	private static DelegateBridge __Hotfix0_OnCheckPassed; // 0x10
	private static DelegateBridge __Hotfix0__DeleteUnusedFiles; // 0x18
	private static DelegateBridge __Hotfix0_UseAsyncCheck; // 0x20
	private static DelegateBridge __Hotfix0__DevOnlyCheckPersistentItems; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override ENode type { get; }

	// RVA: 0x27c1234 VA: 0x7594dd9234
	public override ENode get_type() { }
	// RVA: 0x27c129c VA: 0x7594dd929c
	protected override CheckType GetCheckType() { }
	// RVA: 0x27c1304 VA: 0x7594dd9304
	protected override IEnumerator OnCheckPassed(PersistentResInfo persistentResInfo) { }
	// RVA: 0x27c13fc VA: 0x7594dd93fc
	private Void _DeleteUnusedFiles(PersistentResInfo persistentResInfo) { }
	// RVA: 0x27c17e4 VA: 0x7594dd97e4
	protected override Boolean UseAsyncCheck() { }
	// RVA: 0x27c184c VA: 0x7594dd984c
	private static Void _DevOnlyCheckPersistentItems(PersistentResInfo persistentResInfo) { }
	// RVA: 0x27bfb28 VA: 0x7594dd7b28
	public Void .ctor() { }
}
```