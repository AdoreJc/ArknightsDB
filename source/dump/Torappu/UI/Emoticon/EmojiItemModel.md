# EmojiItemModel

**Namespace:** `Torappu.UI.Emoticon`


## Fields

- `String emojiId`

- `Int32 sortId`

- `String picId`

- `String txt`

- `String themeId`


## Methods

- `Void LoadData(EmojiData, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Emoticon
public class EmojiItemModel : IHotfixable
{
	public String emojiId; // 0x10
	public Int32 sortId; // 0x18
	public String picId; // 0x20
	public String txt; // 0x28
	public String themeId; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x29b6790 VA: 0x7594fce790
	public Void LoadData(EmojiData emojiData, String themeId) { }
	// RVA: 0x29b6720 VA: 0x7594fce720
	public Void .ctor() { }
}
```