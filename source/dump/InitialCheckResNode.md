# InitialCheckResNode

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class InitialCheckResNode : CheckResNode
{
	private static Boolean s_initialBundleDirty; // 0x0
	private static DelegateBridge __Hotfix0_MarkInitialBundleDirty; // 0x8
	private static DelegateBridge __Hotfix0_get_type; // 0x10
	private static DelegateBridge __Hotfix0_GetCheckType; // 0x18
	private static DelegateBridge __Hotfix0_UseAsyncCheck; // 0x20
	private static DelegateBridge __Hotfix0_OnCheckPassed; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override ENode type { get; }

	// RVA: 0x27c0da0 VA: 0x7594dd8da0
	public static Void MarkInitialBundleDirty() { }
	// RVA: 0x27c0e04 VA: 0x7594dd8e04
	public override ENode get_type() { }
	// RVA: 0x27c0e6c VA: 0x7594dd8e6c
	protected override CheckType GetCheckType() { }
	// RVA: 0x27c0ed4 VA: 0x7594dd8ed4
	protected override Boolean UseAsyncCheck() { }
	// RVA: 0x27c0f38 VA: 0x7594dd8f38
	protected override IEnumerator OnCheckPassed(PersistentResInfo persistentResInfo) { }
	// RVA: 0x27bfabc VA: 0x7594dd7abc
	public Void .ctor() { }
}
```