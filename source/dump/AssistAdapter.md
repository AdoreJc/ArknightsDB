# AssistAdapter

**Namespace:** ` `


## Fields

- `EvolvePhaseAndLevel maxEvolvePhaseAndLevel`

- `IPlugin statePlugin`

- `UIFriendEvent applyAssistEvent`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssistAdapter : SimpleLayoutAdapter
{
	public SquadAssistData[] assistList; // 0x20
	public EvolvePhaseAndLevel maxEvolvePhaseAndLevel; // 0x28
	public IPlugin statePlugin; // 0x30
	public UIFriendEvent applyAssistEvent; // 0x38
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x23ca9f4 VA: 0x75949e29f4
	public override Int32 get_count() { }
	// RVA: 0x23caa74 VA: 0x75949e2a74
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x23ca984 VA: 0x75949e2984
	public Void .ctor() { }
}
```