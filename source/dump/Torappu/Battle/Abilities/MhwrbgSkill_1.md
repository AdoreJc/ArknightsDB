# MhwrbgSkill_1

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _cardId`

- `String _cardBuffKey`

- `LifeType _lifeType`

- `Card m_targetCard`

- `Deck m_deck`


## Methods

- `Boolean _TryDrawCardToHand(Deck, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MhwrbgSkill_1 : AbstractAnimatedAbility
{
	private String _cardId; // 0x1c0
	private String _cardBuffKey; // 0x1c8
	private LifeType _lifeType; // 0x1d0
	private Card m_targetCard; // 0x1d8
	private Deck m_deck; // 0x1e0


	// RVA: 0x1e7b0ac VA: 0x75944930ac
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e7b0b4 VA: 0x75944930b4
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e7b0bc VA: 0x75944930bc
	protected override Void OnAttached() { }
	// RVA: 0x1e7b154 VA: 0x7594493154
	protected override Void OnDetached() { }
	// RVA: 0x1e7b1bc VA: 0x75944931bc
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e7b4e0 VA: 0x75944934e0
	private Boolean _TryDrawCardToHand(Deck deck, out Card target) { }
	// RVA: 0x1e7b664 VA: 0x7594493664
	public Void .ctor() { }
}
```