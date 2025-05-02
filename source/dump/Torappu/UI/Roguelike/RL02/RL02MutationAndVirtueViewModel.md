# RL02MutationAndVirtueViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `String topicId`

- `RoguelikeCharBuffModel currMutation`


## Properties

- `Boolean hasMutation`

- `Boolean hasVirtue`


## Methods

- `Boolean get_hasMutation()`

- `Boolean get_hasVirtue()`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02MutationAndVirtueViewModel : RoguelikeMenuCompViewModel
{
	public String topicId; // 0x18
	public RoguelikeCharBuffModel currMutation; // 0x20
	public List`1 mutationCharList; // 0x58
	public List`1 currVirtueList; // 0x60
	private static DelegateBridge __Hotfix0_get_hasMutation; // 0x0
	private static DelegateBridge __Hotfix0_get_hasVirtue; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean hasMutation { get; }
	public Boolean hasVirtue { get; }

	// RVA: 0x2b6bf40 VA: 0x7595183f40
	public Boolean get_hasMutation() { }
	// RVA: 0x2b6bfe4 VA: 0x7595183fe4
	public Boolean get_hasVirtue() { }
	// RVA: 0x2b70db4 VA: 0x7595188db4
	public override Void LoadData(String topicId) { }
	// RVA: 0x2b71420 VA: 0x7595189420
	public Void .ctor() { }
	// RVA: 0x2b71534 VA: 0x7595189534
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```