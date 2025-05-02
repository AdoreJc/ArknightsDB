# RL04AlchemyPoolRarityItemView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `CanvasGroup _canvasItem`

- `UIAnimationLocation _itemBrightAnim`

- `Boolean m_hasInited`

- `ItemSwitchTween m_itemTween`


## Methods

- `Void Render(RandomRewardRarityItemStatus)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyPoolRarityItemView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasItem; // 0x18
	private UIAnimationLocation _itemBrightAnim; // 0x20
	private Boolean m_hasInited; // 0x30
	private ItemSwitchTween m_itemTween; // 0x38
	private const Single DURATION_FOR_FADE_OUT; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b07a38 VA: 0x759511fa38
	public Void Render(RandomRewardRarityItemStatus itemStatus) { }
	// RVA: 0x2b0ac08 VA: 0x7595122c08
	private Void _InitIfNot() { }
	// RVA: 0x2b0ad6c VA: 0x7595122d6c
	public Void .ctor() { }
}
```