# CardBuffWithSkill

**Namespace:** `Torappu.Battle.Skills`


## Fields

- `String _cardBuffKey`

- `LifeType _lifeType`

- `Boolean _dontOccupyDeployCnt`

- `BuildableType _additionBuildableType`

- `AdvancedBuildableMask _additionalBuildableMask`


## Methods

- `Void <>xLuaBaseProxy_DealAttachInDummy(Deck, Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Skills
public class CardBuffWithSkill : Behaviour
{
	private String _cardBuffKey; // 0x20
	private LifeType _lifeType; // 0x28
	private Boolean _dontOccupyDeployCnt; // 0x2c
	private BuildableType _additionBuildableType; // 0x30
	private AdvancedBuildableMask _additionalBuildableMask; // 0x34
	private static DelegateBridge __Hotfix0_DealAttachInDummy; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x1d308f4 VA: 0x75943488f4
	public override Void DealAttachInDummy(Deck deck, Card card) { }
	// RVA: 0x1d30ab4 VA: 0x7594348ab4
	public Void .ctor() { }
	// RVA: 0x1d30b24 VA: 0x7594348b24
	private Void <>xLuaBaseProxy_DealAttachInDummy(Deck P0, Card P1) { }
}
```