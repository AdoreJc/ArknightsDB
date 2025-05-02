# MostCharacterSurroundTileSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _ignoreTargetFree`

- `EntityCategory _AdvancedTargetCategory`

- `Int32 m_maxCharCount`

- `Int32 m_cachedMapHeight`

- `Int32 m_cachedMapWidth`


## Methods

- `Void _ResetInternal()`

- `Void _OnUnitBorn(Object)`

- `Void _OnUnitFinish(Object)`

- `Boolean _CheckSpecifiedEnemies(DoubleBufferedList`1)`

- `FilterType <>xLuaBaseProxy_get_filterType()`

- `Boolean <>xLuaBaseProxy_get_ignoreTargetFree()`

- `EntityCategory <>xLuaBaseProxy_get_targetCategory()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Void <>xLuaBaseProxy__DoFilter(List`1, FilterType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MostCharacterSurroundTileSelector : TileSelector
{
	private List`1 _specifiedEnemyKeys; // 0x148
	private Boolean _ignoreTargetFree; // 0x150
	public EntityCategory _AdvancedTargetCategory; // 0x154
	private Int32[,] m_charCountMap; // 0x158
	private Boolean[,] m_charLocatedMap; // 0x160
	private Int32 m_maxCharCount; // 0x168
	private Int32 m_cachedMapHeight; // 0x16c
	private Int32 m_cachedMapWidth; // 0x170
	private Dictionary`2 m_charDict; // 0x178
	private static DelegateBridge __Hotfix0_get_filterType; // 0x0
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x8
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0__ResetInternal; // 0x20
	private static DelegateBridge __Hotfix0__DoFilter; // 0x28
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x30
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x38
	private static DelegateBridge __Hotfix0__CheckSpecifiedEnemies; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected override FilterType filterType { get; }
	public override Boolean ignoreTargetFree { get; }
	public override EntityCategory targetCategory { get; }

	// RVA: 0x1bc34e8 VA: 0x75941db4e8
	protected override FilterType get_filterType() { }
	// RVA: 0x1bc354c VA: 0x75941db54c
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1bc35b4 VA: 0x75941db5b4
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1bc361c VA: 0x75941db61c
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bc3b14 VA: 0x75941dbb14
	private Void _ResetInternal() { }
	// RVA: 0x1bc3ee4 VA: 0x75941dbee4
	protected override Void _DoFilter(List`1 candidates, FilterType tileFilterType) { }
	// RVA: 0x1bc4984 VA: 0x75941dc984
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x1bc4c54 VA: 0x75941dcc54
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x1bc4564 VA: 0x75941dc564
	private Boolean _CheckSpecifiedEnemies(DoubleBufferedList`1 enemies) { }
	// RVA: 0x1bc4f20 VA: 0x75941dcf20
	public Void .ctor() { }
	// RVA: 0x1bc51e4 VA: 0x75941dd1e4
	private FilterType <>xLuaBaseProxy_get_filterType() { }
	// RVA: 0x1bc5260 VA: 0x75941dd260
	private Boolean <>xLuaBaseProxy_get_ignoreTargetFree() { }
	// RVA: 0x1bc52d8 VA: 0x75941dd2d8
	private EntityCategory <>xLuaBaseProxy_get_targetCategory() { }
	// RVA: 0x1bc5354 VA: 0x75941dd354
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1bc5358 VA: 0x75941dd358
	private Void <>xLuaBaseProxy__DoFilter(List`1 P0, FilterType P1) { }
}
```