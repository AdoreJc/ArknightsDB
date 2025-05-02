# BlockedRandomSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Character m_character`


## Methods

- `Boolean _ValidateWithTargetFree(Entity)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BlockedRandomSelector : RandomSelector
{
	private Character m_character; // 0xc0
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x8
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x10
	private static DelegateBridge __Hotfix0__ValidateWithTargetFree; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ba4a20 VA: 0x75941bca20
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ba4b40 VA: 0x75941bcb40
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1ba5194 VA: 0x75941bd194
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1ba523c VA: 0x75941bd23c
	private Boolean _ValidateWithTargetFree(Entity target) { }
	// RVA: 0x1ba534c VA: 0x75941bd34c
	public Void .ctor() { }
	// RVA: 0x1ba53bc VA: 0x75941bd3bc
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ba53c4 VA: 0x75941bd3c4
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
	// RVA: 0x1ba53cc VA: 0x75941bd3cc
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```