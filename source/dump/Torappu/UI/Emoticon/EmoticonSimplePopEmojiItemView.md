# EmoticonSimplePopEmojiItemView

**Namespace:** `Torappu.UI.Emoticon`


## Fields

- `EmoticonSimpleEmojiItemView _itemPrefab`

- `RectTransform _content`

- `RectTransform _rectPos`

- `UIAnimationLocation _chatItemAnim`

- `CanvasGroup _itemCanvasGroup`

- `Single _popupTime`

- `EmoticonSimpleEmojiItemView m_item`

- `Boolean m_isInited`

- `Tween m_showTween`

- `FadeSwitchTween m_switchTween`


## Methods

- `Void _InitIfNot()`

- `Void <ShowPopupEmojiItem>b__10_0()`

- `Void <ShowPopupEmojiItem>b__10_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Emoticon
public class EmoticonSimplePopEmojiItemView : EmoticonPopEmojiItemBaseView
{
	private EmoticonSimpleEmojiItemView _itemPrefab; // 0x18
	private RectTransform _content; // 0x20
	private RectTransform _rectPos; // 0x28
	private UIAnimationLocation _chatItemAnim; // 0x30
	private CanvasGroup _itemCanvasGroup; // 0x40
	private Single _popupTime; // 0x48
	private EmoticonSimpleEmojiItemView m_item; // 0x50
	private Boolean m_isInited; // 0x58
	private Tween m_showTween; // 0x60
	private FadeSwitchTween m_switchTween; // 0x68
	private static DelegateBridge __Hotfix0_ShowPopupEmojiItem; // 0x0
	private static DelegateBridge __Hotfix0_HidePopupEmojiItem; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29b9a64 VA: 0x7594fd1a64
	public override Void ShowPopupEmojiItem(EmojiItemModel model, GOPositionHolder showPos, ILoadAsset assetLoader, PlayerIndex playerIndex) { }
	// RVA: 0x29b9ef8 VA: 0x7594fd1ef8
	public override Void HidePopupEmojiItem(Boolean isFastMode) { }
	// RVA: 0x29b9d6c VA: 0x7594fd1d6c
	private Void _InitIfNot() { }
	// RVA: 0x29b9fa4 VA: 0x7594fd1fa4
	public Void .ctor() { }
	// RVA: 0x29ba018 VA: 0x7594fd2018
	private Void <ShowPopupEmojiItem>b__10_0() { }
	// RVA: 0x29ba034 VA: 0x7594fd2034
	private Void <ShowPopupEmojiItem>b__10_1() { }
}
```