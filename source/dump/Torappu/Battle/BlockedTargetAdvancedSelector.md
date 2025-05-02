# BlockedTargetAdvancedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _shrinkInTheEnd`

- `Int32 _shrinkNum`

- `Boolean _pickMyTokenFirst`

- `Character m_character`


## Properties

- `Boolean shrinkInTheEnd`


## Methods

- `Boolean get_shrinkInTheEnd()`

- `Int32 <OnPostFilter>b__7_0(Entity, Entity)`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BlockedTargetAdvancedSelector : AdvancedSelector
{
	private Boolean _shrinkInTheEnd; // 0xe8
	private Int32 _shrinkNum; // 0xec
	private Boolean _pickMyTokenFirst; // 0xf0
	private Character m_character; // 0xf8
	private static DelegateBridge __Hotfix0_get_shrinkInTheEnd; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected Boolean shrinkInTheEnd { get; }

	// RVA: 0x1ba637c VA: 0x75941be37c
	protected Boolean get_shrinkInTheEnd() { }
	// RVA: 0x1ba63e4 VA: 0x75941be3e4
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1ba651c VA: 0x75941be51c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1ba67b4 VA: 0x75941be7b4
	public Void .ctor() { }
	// RVA: 0x1ba6824 VA: 0x75941be824
	private Int32 <OnPostFilter>b__7_0(Entity a, Entity b) { }
	// RVA: 0x1ba6ac4 VA: 0x75941beac4
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1ba6acc VA: 0x75941beacc
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```