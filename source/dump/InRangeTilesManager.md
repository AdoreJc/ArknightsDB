# InRangeTilesManager

**Namespace:** ` `


## Fields

- `UInt32 m_updatedInterval`

- `UInt32 m_lastUpdatedFrame`


## Methods

- `Void Init(UInt32)`

- `Boolean Tick()`

- `Void OnCharacterBorn(ObjectPtr`1)`

- `Void OnCharacterFinish(ObjectPtr`1)`

- `Void MarkDirty(Entity)`

- `Void _EnsureList(Entity)`

- `Void _AppendInRangeTile(Character, HashSet`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class InRangeTilesManager : IHotfixable
{
	private static List`1 s_emptyList; // 0x0
	private UInt32 m_updatedInterval; // 0x10
	private UInt32 m_lastUpdatedFrame; // 0x14
	private HashSet`1 m_dirtyCharacter; // 0x18
	private ListDict`2 m_tileInUnitViewRangeBefore; // 0x20
	private HashSet`1 m_inViewTiles; // 0x28
	private static DelegateBridge __Hotfix0_get_inViewTiles; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_Tick; // 0x18
	private static DelegateBridge __Hotfix0_OnCharacterBorn; // 0x20
	private static DelegateBridge __Hotfix0_OnCharacterFinish; // 0x28
	private static DelegateBridge __Hotfix0_MarkDirty; // 0x30
	private static DelegateBridge __Hotfix0__EnsureList; // 0x38
	private static DelegateBridge __Hotfix0__AppendInRangeTile; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public HashSet`1 inViewTiles { get; }

	// RVA: 0x4042544 VA: 0x759665a544
	public HashSet`1 get_inViewTiles() { }
	// RVA: 0x40412c8 VA: 0x75966592c8
	public Void Init(UInt32 frameInterval) { }
	// RVA: 0x4042050 VA: 0x759665a050
	public Boolean Tick() { }
	// RVA: 0x40415c0 VA: 0x75966595c0
	public Void OnCharacterBorn(ObjectPtr`1 entity) { }
	// RVA: 0x4041924 VA: 0x7596659924
	public Void OnCharacterFinish(ObjectPtr`1 entity) { }
	// RVA: 0x40427e4 VA: 0x759665a7e4
	public Void MarkDirty(Entity entity) { }
	// RVA: 0x4042c64 VA: 0x759665ac64
	private Void _EnsureList(Entity character) { }
	// RVA: 0x4042d98 VA: 0x759665ad98
	private Void _AppendInRangeTile(Character character, HashSet`1 tiles) { }
	// RVA: 0x4042ad8 VA: 0x759665aad8
	public Void .ctor() { }
	// RVA: 0x40431f0 VA: 0x759665b1f0
	private static Void .cctor() { }
}
```