# TokenOrHostSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _maxTargetNum`

- `Boolean _checkBuff`

- `String _buffKey`

- `Boolean _isExcluded`

- `Character <character>k__BackingField`


## Properties

- `Boolean checkBuff`

- `Character character`

- `Int32 maxTargetNum`


## Methods

- `Boolean get_checkBuff()`

- `Character get_character()`

- `Void set_character(Character)`

- `Int32 get_maxTargetNum()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TokenOrHostSelector : TargetSelector
{
	private Int32 _maxTargetNum; // 0x30
	private Boolean _checkBuff; // 0x34
	private String _buffKey; // 0x38
	private Boolean _isExcluded; // 0x40
	private Character <character>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_checkBuff; // 0x0
	private static DelegateBridge __Hotfix0_get_character; // 0x8
	private static DelegateBridge __Hotfix0_set_character; // 0x10
	private static DelegateBridge __Hotfix0_get_maxTargetNum; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x28
	private static DelegateBridge __Hotfix0_FindTiles; // 0x30
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Boolean checkBuff { get; }
	protected Character character { get; set; }
	protected Int32 maxTargetNum { get; }

	// RVA: 0x1bd3718 VA: 0x75941eb718
	private Boolean get_checkBuff() { }
	// RVA: 0x1bd3780 VA: 0x75941eb780
	protected Character get_character() { }
	// RVA: 0x1bd37e8 VA: 0x75941eb7e8
	private Void set_character(Character value) { }
	// RVA: 0x1bd386c VA: 0x75941eb86c
	protected Int32 get_maxTargetNum() { }
	// RVA: 0x1bd38e0 VA: 0x75941eb8e0
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bd39dc VA: 0x75941eb9dc
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bd3bbc VA: 0x75941ebbbc
	public override List`1 FindTiles(Vector2 pos) { }
	// RVA: 0x1bd3c3c VA: 0x75941ebc3c
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd3d10 VA: 0x75941ebd10
	public Void .ctor() { }
	// RVA: 0x1bd3d88 VA: 0x75941ebd88
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
}
```