# NecromancerQueueTileSelector

**Namespace:** `Torappu.Battle`


## Fields

- `NecromancerFilterType _necromancerFilterType`

- `Boolean _useOtherSelectorQueue`

- `String _selectorAbilityName`

- `Boolean _verifyQueueTile`

- `Boolean _verifyInRange`


## Methods

- `Void PushTileIntoQueue(Tile)`

- `Void <>xLuaBaseProxy__DoFilter(List`1, FilterType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class NecromancerQueueTileSelector : TileSelector
{
	protected NecromancerFilterType _necromancerFilterType; // 0x148
	private Boolean _useOtherSelectorQueue; // 0x14c
	private String _selectorAbilityName; // 0x150
	private Boolean _verifyQueueTile; // 0x158
	private Boolean _verifyInRange; // 0x159
	protected Queue`1 m_tileQueue; // 0x160
	private static DelegateBridge __Hotfix0_get_tileQueue; // 0x0
	private static DelegateBridge __Hotfix0_PushTileIntoQueue; // 0x8
	private static DelegateBridge __Hotfix0__DoFilter; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Queue`1 tileQueue { get; }

	// RVA: 0x1bcc1b8 VA: 0x75941e41b8
	public Queue`1 get_tileQueue() { }
	// RVA: 0x1bcc3a4 VA: 0x75941e43a4
	public Void PushTileIntoQueue(Tile tile) { }
	// RVA: 0x1bcc448 VA: 0x75941e4448
	protected override Void _DoFilter(List`1 candidates, FilterType tileFilterType) { }
	// RVA: 0x1bcccf4 VA: 0x75941e4cf4
	public Void .ctor() { }
	// RVA: 0x1bccd84 VA: 0x75941e4d84
	private Void <>xLuaBaseProxy__DoFilter(List`1 P0, FilterType P1) { }
}
```