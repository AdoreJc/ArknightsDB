# EmoticonSimpleThemeItemView

**Namespace:** `Torappu.UI.Emoticon`


## Fields

- `SimpleLayoutContent _emojiItemContent`

- `Boolean m_isInited`

- `EmoticonThemeItemModel m_cachedModel`

- `EmojiItemAdapter m_emojiItemAdapter`

- `ILoadAsset m_cachedAssetLoader`


## Methods

- `Void Render(EmoticonThemeItemModel, ILoadAsset)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Emoticon
public class EmoticonSimpleThemeItemView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _emojiItemContent; // 0x18
	private Boolean m_isInited; // 0x20
	private EmoticonThemeItemModel m_cachedModel; // 0x28
	private EmojiItemAdapter m_emojiItemAdapter; // 0x30
	private ILoadAsset m_cachedAssetLoader; // 0x38
	public Action`2 onClickEmojiItem; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29b93e8 VA: 0x7594fd13e8
	public Void Render(EmoticonThemeItemModel model, ILoadAsset assetLoader) { }
	// RVA: 0x29ba050 VA: 0x7594fd2050
	private Void _InitIfNot() { }
	// RVA: 0x29ba1b4 VA: 0x7594fd21b4
	public Void .ctor() { }
}
```