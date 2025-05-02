# CreateDeckBuff

**Namespace:** ` `


## Fields

- `DeckBuff _deckBuff`

- `Boolean _randomOneDeckCard`

- `Boolean _filterIsInHand`

- `Boolean _exceptTokenAndTrap`

- `Boolean _onlyTokenAndTrap`

- `Boolean _excludeTarget`

- `Boolean _onlyToTarget`

- `ActionTargetType _target`


## Methods

- `Void _CollectCard(Card[], Character)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateDeckBuff : ActionNode
{
	private DeckBuff _deckBuff; // 0x10
	private Boolean _randomOneDeckCard; // 0x30
	private Boolean _filterIsInHand; // 0x31
	private Boolean _exceptTokenAndTrap; // 0x32
	private Boolean _onlyTokenAndTrap; // 0x33
	private Boolean _excludeTarget; // 0x34
	private Boolean _onlyToTarget; // 0x35
	private ActionTargetType _target; // 0x38
	private List`1 m_cards; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__CollectCard; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f4dbac VA: 0x7594565bac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4dc14 VA: 0x7594565c14
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4e0a0 VA: 0x75945660a0
	private Void _CollectCard(Card[] cards, Character targetCanbeNull) { }
	// RVA: 0x1f4e324 VA: 0x7594566324
	public Void .ctor() { }
}
```