# AudioManager

**Namespace:** ` `


## Fields

- `SeqNumChecker m_effInfoSeqNumChecker`

- `SeqNumChecker m_refreshSeqNumChecker`

- `SeqNumChecker m_frozenSeqNumChecker`

- `SeqNumChecker m_upgradeSeqNumChecker`

- `Vector3 m_shopTileCenterWorldPos`

- `Vector3 m_battleTileCenterWorldPos`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot(AutoChessDataCenter)`

- `Void TryEmitWhenPlane(AutoChessDataCenter)`

- `Void TryEmit(AutoChessDataCenter)`

- `Void TryEmitWhenTimeChanged(AutoChessDataCenter)`

- `Void TryEmitGameOver(AutoChessDataCenter)`

- `Void _TryEmitRefreshResponse(AutoChessDataCenter)`

- `Void _TryEmitUpgradeResponse(AutoChessDataCenter)`

- `Void _TryEmitLockUnlockResponse(AutoChessDataCenter)`

- `Void _PlayLockOrUnlock(AutoChessDataCenter)`

- `Void _EmitEffectInfos(AutoChessDataCenter)`

- `Void _PlayShopPlacedIfHasCharacter()`

- `Void _DoPlayShopPlaced()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AudioManager : IHotfixable
{
	private const Single DELAY_SHOP_DEPLOY_TIME; // 0x0
	private SeqNumChecker m_effInfoSeqNumChecker; // 0x10
	private SeqNumChecker m_refreshSeqNumChecker; // 0x18
	private SeqNumChecker m_frozenSeqNumChecker; // 0x20
	private SeqNumChecker m_upgradeSeqNumChecker; // 0x28
	private Vector3 m_shopTileCenterWorldPos; // 0x30
	private Vector3 m_battleTileCenterWorldPos; // 0x3c
	private Boolean m_inited; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_TryEmitWhenPlane; // 0x8
	private static DelegateBridge __Hotfix0_TryEmit; // 0x10
	private static DelegateBridge __Hotfix0_TryEmitWhenTimeChanged; // 0x18
	private static DelegateBridge __Hotfix0_TryEmitGameOver; // 0x20
	private static DelegateBridge __Hotfix0__TryEmitRefreshResponse; // 0x28
	private static DelegateBridge __Hotfix0__TryEmitUpgradeResponse; // 0x30
	private static DelegateBridge __Hotfix0__TryEmitLockUnlockResponse; // 0x38
	private static DelegateBridge __Hotfix0__PlayLockOrUnlock; // 0x40
	private static DelegateBridge __Hotfix0__EmitEffectInfos; // 0x48
	private static DelegateBridge __Hotfix0__PlayShopPlacedIfHasCharacter; // 0x50
	private static DelegateBridge __Hotfix0__DoPlayShopPlaced; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x206f23c VA: 0x759468723c
	public Void _InitIfNot(AutoChessDataCenter center) { }
	// RVA: 0x206c4f4 VA: 0x75946844f4
	public Void TryEmitWhenPlane(AutoChessDataCenter center) { }
	// RVA: 0x206ced0 VA: 0x7594684ed0
	public Void TryEmit(AutoChessDataCenter center) { }
	// RVA: 0x206ccdc VA: 0x7594684cdc
	public Void TryEmitWhenTimeChanged(AutoChessDataCenter center) { }
	// RVA: 0x206c914 VA: 0x7594684914
	public Void TryEmitGameOver(AutoChessDataCenter center) { }
	// RVA: 0x206f688 VA: 0x7594687688
	private Void _TryEmitRefreshResponse(AutoChessDataCenter center) { }
	// RVA: 0x206f78c VA: 0x759468778c
	private Void _TryEmitUpgradeResponse(AutoChessDataCenter center) { }
	// RVA: 0x206f888 VA: 0x7594687888
	private Void _TryEmitLockUnlockResponse(AutoChessDataCenter center) { }
	// RVA: 0x206fa30 VA: 0x7594687a30
	private Void _PlayLockOrUnlock(AutoChessDataCenter center) { }
	// RVA: 0x206f340 VA: 0x7594687340
	private Void _EmitEffectInfos(AutoChessDataCenter center) { }
	// RVA: 0x206fb28 VA: 0x7594687b28
	private Void _PlayShopPlacedIfHasCharacter() { }
	// RVA: 0x206f948 VA: 0x7594687948
	private Void _DoPlayShopPlaced() { }
	// RVA: 0x206f0e0 VA: 0x75946870e0
	public Void .ctor() { }
}
```