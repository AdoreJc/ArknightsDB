# RL04AlchemyFragmentStorageView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `CanvasGroup _canvasEmpty`

- `CanvasGroup _canvasStorageList`

- `RL04AlchemyFragmentListTitleItemView _titleItemPrefab`

- `RL04AlchemyFragmentListRowItemView _rowItemPrefab`

- `UIRecycleVerticalLayoutGroup _recycleList`

- `ScrollRect _scrollRect`

- `Boolean m_hasInited`

- `FadeSwitchTween m_tweenEmpty`

- `FadeSwitchTween m_tweenStorageList`

- `Int32 m_cachedEnterSequenceNum`

- `Int32 m_cachedListRefreshSequenceNum`

- `RL04AlchemyFragmentListAdapter m_adapter`


## Methods

- `Void Render(RL04AlchemyFragmentListViewModel)`

- `Void ResetViewSeqCache()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyFragmentStorageView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasEmpty; // 0x18
	private CanvasGroup _canvasStorageList; // 0x20
	private RL04AlchemyFragmentListTitleItemView _titleItemPrefab; // 0x28
	private RL04AlchemyFragmentListRowItemView _rowItemPrefab; // 0x30
	private UIRecycleVerticalLayoutGroup _recycleList; // 0x38
	private ScrollRect _scrollRect; // 0x40
	private Boolean m_hasInited; // 0x48
	private FadeSwitchTween m_tweenEmpty; // 0x50
	private FadeSwitchTween m_tweenStorageList; // 0x58
	private Int32 m_cachedEnterSequenceNum; // 0x60
	private Int32 m_cachedListRefreshSequenceNum; // 0x64
	private RL04AlchemyFragmentListAdapter m_adapter; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ResetViewSeqCache; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b0926c VA: 0x759512126c
	public Void Render(RL04AlchemyFragmentListViewModel fragmentListViewModel) { }
	// RVA: 0x2b09c54 VA: 0x7595121c54
	public Void ResetViewSeqCache() { }
	// RVA: 0x2b093c4 VA: 0x75951213c4
	private Void _InitIfNot() { }
	// RVA: 0x2b09da4 VA: 0x7595121da4
	public Void .ctor() { }
}
```