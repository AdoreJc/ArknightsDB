# ShopStateRuneManager

**Namespace:** ` `


## Methods

- `Void _ConstructorImpl()`

- `Void Handle(BattleCharacterData, Int32, String)`

- `Void CollectTags(List`1, Int32)`

- `Void _ProcessCultivate(BattleCharacterData, String)`

- `Void _ProcessEquip(List`1, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ShopStateRuneManager : IHotfixable
{
	private ListDict`2 m_buffs; // 0x10
	private Dictionary`2 m_handlers; // 0x18
	private static List`1 s_equipEffectIds; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0__ConstructorImpl; // 0x10
	private static DelegateBridge __Hotfix0_get_buffs; // 0x18
	private static DelegateBridge __Hotfix0_Handle; // 0x20
	private static DelegateBridge __Hotfix0_CollectTags; // 0x28
	private static DelegateBridge __Hotfix0__ProcessCultivate; // 0x30
	private static DelegateBridge __Hotfix0__ProcessEquip; // 0x38

	private ListDict`2 buffs { get; }

	// RVA: 0x1ca9ebc VA: 0x75942c1ebc
	public Void .ctor() { }
	// RVA: 0x1ca9fe8 VA: 0x75942c1fe8
	private Void _ConstructorImpl() { }
	// RVA: 0x1caa6fc VA: 0x75942c26fc
	private ListDict`2 get_buffs() { }
	// RVA: 0x1ca7440 VA: 0x75942bf440
	public Void Handle(BattleCharacterData target, Int32 instId, String chessId) { }
	// RVA: 0x1caa9fc VA: 0x75942c29fc
	public Void CollectTags(List`1 tags, Int32 instId) { }
	// RVA: 0x1caa774 VA: 0x75942c2774
	private Void _ProcessCultivate(BattleCharacterData target, String chessId) { }
	// RVA: 0x1caaab0 VA: 0x75942c2ab0
	private Void _ProcessEquip(List`1 tags, Int32 instId) { }
	// RVA: 0x1caaedc VA: 0x75942c2edc
	private static Void .cctor() { }
}
```