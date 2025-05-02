# ActivityEntryKVSwitchComponent

**Namespace:** `Torappu.Activity`


## Methods

- `String _FindValidKVId(ListDict`2)`

- `Void _SetKVImgs(String, String)`

- `Void <>xLuaBaseProxy_OnLoaded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityEntryKVSwitchComponent : ActivityStageComponent, IHotfixable
{
	private Image[] _kvImgs; // 0x20
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x0
	private static DelegateBridge __Hotfix0__FindValidKVId; // 0x8
	private static DelegateBridge __Hotfix0__SetKVImgs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30baeb8 VA: 0x75956d2eb8
	protected override Void OnLoaded() { }
	// RVA: 0x30bb060 VA: 0x75956d3060
	private String _FindValidKVId(ListDict`2 kvSwitchInfos) { }
	// RVA: 0x30bb1f8 VA: 0x75956d31f8
	private Void _SetKVImgs(String kvId, String actId) { }
	// RVA: 0x30bb390 VA: 0x75956d3390
	public Void .ctor() { }
	// RVA: 0x30bb3fc VA: 0x75956d33fc
	private Void <>xLuaBaseProxy_OnLoaded() { }
}
```