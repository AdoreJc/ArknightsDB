# RoguelikeMenuZoneViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String currZoneId`

- `String currZoneName`

- `String currZoneDesc`

- `RoguelikeVariationModel currVariation1`

- `RoguelikeVariationModel currVariation2`


## Methods

- `Boolean HasVariation()`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuZoneViewModel : RoguelikeMenuCompViewModel
{
	public String currZoneId; // 0x18
	public String currZoneName; // 0x20
	public String currZoneDesc; // 0x28
	public RoguelikeVariationModel currVariation1; // 0x30
	public RoguelikeVariationModel currVariation2; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_HasVariation; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2a7e25c VA: 0x759509625c
	public override Void LoadData(String topicId) { }
	// RVA: 0x2a7e5c4 VA: 0x75950965c4
	public Boolean HasVariation() { }
	// RVA: 0x2a7e63c VA: 0x759509663c
	public Void .ctor() { }
	// RVA: 0x2a7e6a8 VA: 0x75950966a8
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```