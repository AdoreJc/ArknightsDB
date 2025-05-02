# VoteCarViewModel

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Boolean hasNewEquipment`

- `Boolean isNpc`

- `String npcId`

- `String npcName`

- `String npcPicId`

- `SpriteRenderData npcPic`

- `Boolean canRequest`

- `ExhibitionFriendCard friendCard`

- `Cart car`


## Methods

- `Void LoadData(String, ExhibitionShowItem)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class VoteCarViewModel : IHotfixable
{
	public Boolean hasNewEquipment; // 0x10
	public Boolean isNpc; // 0x11
	public String npcId; // 0x18
	public String npcName; // 0x20
	public String npcPicId; // 0x28
	public SpriteRenderData npcPic; // 0x30
	public Boolean canRequest; // 0x58
	public ExhibitionFriendCard friendCard; // 0x60
	public Cart car; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x330278c VA: 0x759591a78c
	public Void LoadData(String actId, ExhibitionShowItem showItem) { }
	// RVA: 0x33028f4 VA: 0x759591a8f4
	public Void .ctor() { }
}
```