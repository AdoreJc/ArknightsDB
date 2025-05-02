# UICooperateBattleEmoticonPopItemView

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UICooperateBattleEmoticonItemView _itemSelf`

- `UICooperateBattleEmoticonItemView _itemMate`

- `UIAnimationLocation _popEmojiAnimSelf`

- `UIAnimationLocation _popEmojiAnimMate`

- `RectTransform _posHandler`

- `Tween m_tween`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattleEmoticonPopItemView : EmoticonPopEmojiItemBaseView
{
	private UICooperateBattleEmoticonItemView _itemSelf; // 0x18
	private UICooperateBattleEmoticonItemView _itemMate; // 0x20
	private UIAnimationLocation _popEmojiAnimSelf; // 0x28
	private UIAnimationLocation _popEmojiAnimMate; // 0x38
	private RectTransform _posHandler; // 0x48
	private Tween m_tween; // 0x50
	private static DelegateBridge __Hotfix0_ShowPopupEmojiItem; // 0x0
	private static DelegateBridge __Hotfix0_HidePopupEmojiItem; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x20e2520 VA: 0x75946fa520
	public override Void ShowPopupEmojiItem(EmojiItemModel model, GOPositionHolder showPos, ILoadAsset assetLoader, PlayerIndex playerIndex) { }
	// RVA: 0x20e2874 VA: 0x75946fa874
	public override Void HidePopupEmojiItem(Boolean isFastMode) { }
	// RVA: 0x20e28ec VA: 0x75946fa8ec
	public Void .ctor() { }
}
```