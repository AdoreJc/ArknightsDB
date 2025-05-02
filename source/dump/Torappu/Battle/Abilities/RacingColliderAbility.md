# RacingColliderAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _collisionEffect`

- `Collider2D m_collider`


## Methods

- `Void _DealCollisionWithRacingEnemy(Collider2D)`

- `Void _DealCollisionWithWall(Collider2D)`

- `Boolean _CheckCollisionCondition(RacingEnemy, RacingEnemy)`

- `Void _PlayEffect()`

- `Void OnTriggerEnter2D(Collider2D)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RacingColliderAbility : EmptyAbility
{
	private String _collisionEffect; // 0x108
	private ObjectPtr`1 m_racingEnemy; // 0x110
	private Collider2D m_collider; // 0x120
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x8
	private static DelegateBridge __Hotfix0_DoDetach; // 0x10
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0x18
	private static DelegateBridge __Hotfix0__DealCollisionWithRacingEnemy; // 0x20
	private static DelegateBridge __Hotfix0__DealCollisionWithWall; // 0x28
	private static DelegateBridge __Hotfix0__CheckCollisionCondition; // 0x30
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x38
	private static DelegateBridge __Hotfix0__PlayEffect; // 0x40
	private static DelegateBridge __Hotfix0_OnTriggerEnter2D; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x1e4e808 VA: 0x7594466808
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e4e970 VA: 0x7594466970
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e4ea58 VA: 0x7594466a58
	protected override Void DoDetach() { }
	// RVA: 0x1e4eb24 VA: 0x7594466b24
	public override Void PreloadSpecialAudioSignals(String characterId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1e4ec14 VA: 0x7594466c14
	private Void _DealCollisionWithRacingEnemy(Collider2D collision) { }
	// RVA: 0x1e4f074 VA: 0x7594467074
	private Void _DealCollisionWithWall(Collider2D collision) { }
	// RVA: 0x1e4ed54 VA: 0x7594466d54
	private Boolean _CheckCollisionCondition(RacingEnemy self, RacingEnemy another) { }
	// RVA: 0x1e4f14c VA: 0x759446714c
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e4ee50 VA: 0x7594466e50
	private Void _PlayEffect() { }
	// RVA: 0x1e4f270 VA: 0x7594467270
	private Void OnTriggerEnter2D(Collider2D collision) { }
	// RVA: 0x1e4f424 VA: 0x7594467424
	public Void .ctor() { }
	// RVA: 0x1e4f494 VA: 0x7594467494
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e4f4bc VA: 0x75944674bc
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e4f4c4 VA: 0x75944674c4
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e4f4cc VA: 0x75944674cc
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
	// RVA: 0x1e4f4d4 VA: 0x75944674d4
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```