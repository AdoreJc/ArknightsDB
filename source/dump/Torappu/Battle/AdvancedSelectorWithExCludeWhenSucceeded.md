# AdvancedSelectorWithExCludeWhenSucceeded

**Namespace:** `Torappu.Battle`


## Methods

- `Void AddSucceededTarget(Entity)`

- `Void ClearSucceededTarget()`

- `Void <>xLuaBaseProxy_Awake()`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithExCludeWhenSucceeded : AdvancedSelector
{
	private ListSet`1 m_succeededTargetList; // 0xe8
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x8
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x10
	private static DelegateBridge __Hotfix0_AddSucceededTarget; // 0x18
	private static DelegateBridge __Hotfix0_ClearSucceededTarget; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1b9b264 VA: 0x75941b3264
	protected override Void Awake() { }
	// RVA: 0x1b9b35c VA: 0x75941b335c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1b9b488 VA: 0x75941b3488
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1b9b588 VA: 0x75941b3588
	public Void AddSucceededTarget(Entity target) { }
	// RVA: 0x1b9b2d4 VA: 0x75941b32d4
	public Void ClearSucceededTarget() { }
	// RVA: 0x1b9b628 VA: 0x75941b3628
	public Void .ctor() { }
	// RVA: 0x1b9b6e8 VA: 0x75941b36e8
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x1b9b6ec VA: 0x75941b36ec
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
	// RVA: 0x1b9b6f0 VA: 0x75941b36f0
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
}
```