# EmoticonThemeItemModel

**Namespace:** `Torappu.UI.Emoticon`


## Fields

- `String themeId`

- `Int32 sortId`

- `String name`


## Methods

- `Boolean TryLoadData(String, EmojiSceneType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Emoticon
public class EmoticonThemeItemModel : IHotfixable
{
	public String themeId; // 0x10
	public Int32 sortId; // 0x18
	public String name; // 0x20
	public List`1 emojiItemModels; // 0x28
	private static DelegateBridge __Hotfix0_TryLoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x29b6060 VA: 0x7594fce060
	public Boolean TryLoadData(String themeId, EmojiSceneType chatSceneType) { }
	// RVA: 0x29b5f9c VA: 0x7594fcdf9c
	public Void .ctor() { }
}
```