# BlockedOrAdvancedSelectorWithRestPostSort

**Namespace:** `Torappu.Battle`


## Fields

- `String _postSortTag`

- `String _excludeBuffKey`

- `Boolean _hasPriorAbnormalFlag`

- `AbnormalFlag _priorAbnormalFlag`


## Properties

- `Boolean hasPriorAbnormalFlag`


## Methods

- `Boolean get_hasPriorAbnormalFlag()`

- `Int32 <OnPostFilter>b__6_0(Entity, Entity)`

- `Int32 <OnPostFilter>b__6_1(Entity, Entity)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BlockedOrAdvancedSelectorWithRestPostSort : BlockedOrAdvancedSelector
{
	private String _postSortTag; // 0x100
	private String _excludeBuffKey; // 0x108
	private Boolean _hasPriorAbnormalFlag; // 0x110
	private AbnormalFlag _priorAbnormalFlag; // 0x114
	private static DelegateBridge __Hotfix0_get_hasPriorAbnormalFlag; // 0x0
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	private Boolean hasPriorAbnormalFlag { get; }

	// RVA: 0x1ba3c20 VA: 0x75941bbc20
	private Boolean get_hasPriorAbnormalFlag() { }
	// RVA: 0x1ba3c88 VA: 0x75941bbc88
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1ba3840 VA: 0x75941bb840
	public Void .ctor() { }
	// RVA: 0x1ba3fec VA: 0x75941bbfec
	private Int32 <OnPostFilter>b__6_0(Entity a, Entity b) { }
	// RVA: 0x1ba4060 VA: 0x75941bc060
	private Int32 <OnPostFilter>b__6_1(Entity a, Entity b) { }
	// RVA: 0x1ba40d8 VA: 0x75941bc0d8
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```