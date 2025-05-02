# RoguelikeActivityPredefineSeedItemModel

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `String predefineDesc`

- `Int64 m_sortId`


## Methods

- `Void LoadData(RoguelikeActivityOfficialSeedData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivityPredefineSeedItemModel : RoguelikeActivitySeedItemModel
{
	public static readonly RoguelikeActivityPredefineSeedItemModel EMPTY_ITEM; // 0x0
	public String predefineDesc; // 0x20
	private Int64 m_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_seedItemType; // 0x8
	private static DelegateBridge __Hotfix0_get_sortId; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SeedItemType seedItemType { get; }
	public override Int64 sortId { get; }

	// RVA: 0x26e3478 VA: 0x7594cfb478
	public override SeedItemType get_seedItemType() { }
	// RVA: 0x26e34f0 VA: 0x7594cfb4f0
	public override Int64 get_sortId() { }
	// RVA: 0x26e2e38 VA: 0x7594cfae38
	public Void LoadData(RoguelikeActivityOfficialSeedData predefine) { }
	// RVA: 0x26e2dbc VA: 0x7594cfadbc
	public Void .ctor() { }
	// RVA: 0x26e3568 VA: 0x7594cfb568
	private static Void .cctor() { }
}
```