# SandboxV2RiftRewardItemCard

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAnimationLocation _rewardAnim`

- `SandboxV2ItemCard _itemCardPrefab`

- `RectTransform _itemCardContainer`

- `SandboxV2ItemCard m_itemCard`

- `UIItemViewModel m_cachedItemViewModel`

- `Tween m_tween`

- `Boolean m_hasInited`


## Methods

- `Void Render(Int32, UIItemViewModel)`

- `Void PlayRewardAnim(Single)`

- `Void ResetTween(Boolean)`

- `Void _InitIfNot()`

- `Void _EventOnItemClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftRewardItemCard : MonoBehaviour, IHotfixable
{
	private static readonly Option REWARD_ITEM_CARD_OPTION; // 0x0
	private UIAnimationLocation _rewardAnim; // 0x18
	private SandboxV2ItemCard _itemCardPrefab; // 0x28
	private RectTransform _itemCardContainer; // 0x30
	private SandboxV2ItemCard m_itemCard; // 0x38
	private UIItemViewModel m_cachedItemViewModel; // 0x40
	private Tween m_tween; // 0x48
	private Boolean m_hasInited; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_PlayRewardAnim; // 0x28
	private static DelegateBridge __Hotfix0_ResetTween; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__EventOnItemClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x251a6b0 VA: 0x7594b326b0
	public Void Render(Int32 idx, UIItemViewModel itemViewModel) { }
	// RVA: 0x251a920 VA: 0x7594b32920
	public Void PlayRewardAnim(Single delay) { }
	// RVA: 0x251aaa0 VA: 0x7594b32aa0
	public Void ResetTween(Boolean isEnd) { }
	// RVA: 0x251a770 VA: 0x7594b32770
	private Void _InitIfNot() { }
	// RVA: 0x251ab90 VA: 0x7594b32b90
	private Void _EventOnItemClick(Int32 idx) { }
	// RVA: 0x251ac94 VA: 0x7594b32c94
	public Void .ctor() { }
	// RVA: 0x251ad14 VA: 0x7594b32d14
	private static Void .cctor() { }
}
```