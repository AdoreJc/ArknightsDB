# EmoticonResHolder

**Namespace:** `Torappu.UI.Emoticon`


## Fields

- `Sprite _emojiBgSprite`

- `AutoPackSpriteHub _emojiIconHub`

- `Color _emojiTxtColor`


## Methods

- `Sprite GetEmojiBgSprite()`

- `Color GetEmojiTxtColor()`

- `Sprite GetEmojiIconFromHub(String, ILoadAsset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Emoticon
public class EmoticonResHolder : MonoBehaviour, IHotfixable
{
	private Sprite _emojiBgSprite; // 0x18
	private AutoPackSpriteHub _emojiIconHub; // 0x20
	private Color _emojiTxtColor; // 0x28
	private static DelegateBridge __Hotfix0_GetEmojiBgSprite; // 0x0
	private static DelegateBridge __Hotfix0_GetEmojiTxtColor; // 0x8
	private static DelegateBridge __Hotfix0_GetEmojiIconFromHub; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29b71f0 VA: 0x7594fcf1f0
	public Sprite GetEmojiBgSprite() { }
	// RVA: 0x29b7258 VA: 0x7594fcf258
	public Color GetEmojiTxtColor() { }
	// RVA: 0x29b72c0 VA: 0x7594fcf2c0
	public Sprite GetEmojiIconFromHub(String iconId, ILoadAsset assetLoader) { }
	// RVA: 0x29b7400 VA: 0x7594fcf400
	public Void .ctor() { }
}
```