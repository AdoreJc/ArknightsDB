# AttachListenerToTileAbility

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void _ClearListeners()`

- `Void _ClearEffects()`

- `Void AttachToTile(Tile)`

- `Void _OnUnitReborn(Object)`

- `Void _OnRallyPointReborn(Object)`

- `Int32 GetTileCastedTimes(Tile)`

- `Void RefreshTileStatus()`

- `Void SyncStatusFromOtherAbility(AttachListenerToTileAbility)`

- `Boolean <>xLuaBaseProxy_CheckIsDamageOrHealSource()`

- `Boolean <>xLuaBaseProxy_get_isReady()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_Awake()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AttachListenerToTileAbility : CastOnTileAbility
{
	private AttachEffectSetting[] _effectSettings; // 0x1f8
	private AttachableTileListener[] m_listeners; // 0x200
	private Dictionary`2 m_tileCastedStatus; // 0x208
	private Dictionary`2 m_castedTileEffect; // 0x210
	private static DelegateBridge __Hotfix0_get_tileCastedStatus; // 0x0
	private static DelegateBridge __Hotfix0_CheckIsDamageOrHealSource; // 0x8
	private static DelegateBridge __Hotfix0_get_isReady; // 0x10
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x18
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x20
	private static DelegateBridge __Hotfix0_Awake; // 0x28
	private static DelegateBridge __Hotfix0_DoSetData; // 0x30
	private static DelegateBridge __Hotfix0_DoAttach; // 0x38
	private static DelegateBridge __Hotfix0_DoDetach; // 0x40
	private static DelegateBridge __Hotfix0_Reset; // 0x48
	private static DelegateBridge __Hotfix0_OnDetached; // 0x50
	private static DelegateBridge __Hotfix0__ClearListeners; // 0x58
	private static DelegateBridge __Hotfix0__ClearEffects; // 0x60
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x68
	private static DelegateBridge __Hotfix0_AttachToTile; // 0x70
	private static DelegateBridge __Hotfix0__OnUnitReborn; // 0x78
	private static DelegateBridge __Hotfix0__OnRallyPointReborn; // 0x80
	private static DelegateBridge __Hotfix0_GetTileCastedTimes; // 0x88
	private static DelegateBridge __Hotfix0_RefreshTileStatus; // 0x90
	private static DelegateBridge __Hotfix0_SyncStatusFromOtherAbility; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	private Dictionary`2 tileCastedStatus { get; }
	public override Boolean isReady { get; }

	// RVA: 0x1e222b8 VA: 0x759443a2b8
	private Dictionary`2 get_tileCastedStatus() { }
	// RVA: 0x1e22320 VA: 0x759443a320
	protected override Boolean CheckIsDamageOrHealSource() { }
	// RVA: 0x1e22384 VA: 0x759443a384
	public override Boolean get_isReady() { }
	// RVA: 0x1e223ec VA: 0x759443a3ec
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e22464 VA: 0x759443a464
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e2279c VA: 0x759443a79c
	protected override Void Awake() { }
	// RVA: 0x1e22904 VA: 0x759443a904
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e22a10 VA: 0x759443aa10
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e22bb0 VA: 0x759443abb0
	protected override Void DoDetach() { }
	// RVA: 0x1e22d44 VA: 0x759443ad44
	protected override Void Reset() { }
	// RVA: 0x1e23208 VA: 0x759443b208
	protected override Void OnDetached() { }
	// RVA: 0x1e22dc0 VA: 0x759443adc0
	private Void _ClearListeners() { }
	// RVA: 0x1e22fdc VA: 0x759443afdc
	private Void _ClearEffects() { }
	// RVA: 0x1e23474 VA: 0x759443b474
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e236bc VA: 0x759443b6bc
	public Void AttachToTile(Tile tile) { }
	// RVA: 0x1e23b64 VA: 0x759443bb64
	private Void _OnUnitReborn(Object arg) { }
	// RVA: 0x1e23cd0 VA: 0x759443bcd0
	private Void _OnRallyPointReborn(Object arg) { }
	// RVA: 0x1e23ec0 VA: 0x759443bec0
	public Int32 GetTileCastedTimes(Tile tile) { }
	// RVA: 0x1e23fb0 VA: 0x759443bfb0
	public Void RefreshTileStatus() { }
	// RVA: 0x1e241a4 VA: 0x759443c1a4
	public Void SyncStatusFromOtherAbility(AttachListenerToTileAbility ability) { }
	// RVA: 0x1e24528 VA: 0x759443c528
	public Void .ctor() { }
	// RVA: 0x1e24638 VA: 0x759443c638
	private Boolean <>xLuaBaseProxy_CheckIsDamageOrHealSource() { }
	// RVA: 0x1e24640 VA: 0x759443c640
	private Boolean <>xLuaBaseProxy_get_isReady() { }
	// RVA: 0x1e24648 VA: 0x759443c648
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1e2464c VA: 0x759443c64c
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x1e24654 VA: 0x759443c654
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e2467c VA: 0x759443c67c
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e24684 VA: 0x759443c684
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e2468c VA: 0x759443c68c
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e24694 VA: 0x759443c694
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e24698 VA: 0x759443c698
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
}
```