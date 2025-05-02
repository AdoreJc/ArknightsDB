# CommonReplicateItemCard

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _commonItemRoot`

- `RectTransform _repItemRoot`

- `GameObject _repIcon`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `UIItemCard m_repItemCard`

- `ReplicateTweenWrapper m_repTween`

- `UIItemViewModel m_itemModel`

- `UIItemViewModel m_repItemModel`

- `Boolean m_isReplicate`


## Methods

- `Void Render(InputParams)`

- `Void UpdateCardColorByCompleteStatus(Boolean, Color, Color)`

- `Void OnDestroy()`

- `Void _InitIfNot()`

- `Void _RenderCommonItemCard(InputParams)`

- `Void _RenderRepItemCard(InputParams)`

- `UIItemCard _EnsureCommonItemCard(Single)`

- `UIItemCard _EnsureRepItemCard(Single)`

- `Void _ShowCard(UIItemCard, Boolean)`

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CommonReplicateItemCard : MonoBehaviour, IHotfixable
{
	private RectTransform _commonItemRoot; // 0x18
	private RectTransform _repItemRoot; // 0x20
	private GameObject _repIcon; // 0x28
	private Boolean m_isInited; // 0x30
	private UIItemCard m_itemCard; // 0x38
	private UIItemCard m_repItemCard; // 0x40
	private ReplicateTweenWrapper m_repTween; // 0x48
	private UIItemViewModel m_itemModel; // 0x50
	private UIItemViewModel m_repItemModel; // 0x58
	private Boolean m_isReplicate; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_UpdateCardColorByCompleteStatus; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RenderCommonItemCard; // 0x20
	private static DelegateBridge __Hotfix0__RenderRepItemCard; // 0x28
	private static DelegateBridge __Hotfix0__EnsureCommonItemCard; // 0x30
	private static DelegateBridge __Hotfix0__EnsureRepItemCard; // 0x38
	private static DelegateBridge __Hotfix0__ShowCard; // 0x40
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2188454 VA: 0x75947a0454
	public Void Render(InputParams inputParams) { }
	// RVA: 0x2188978 VA: 0x75947a0978
	public Void UpdateCardColorByCompleteStatus(Boolean isCompleted, Color completeCol, Color normalCol) { }
	// RVA: 0x2188c48 VA: 0x75947a0c48
	protected Void OnDestroy() { }
	// RVA: 0x218851c VA: 0x75947a051c
	private Void _InitIfNot() { }
	// RVA: 0x2188678 VA: 0x75947a0678
	private Void _RenderCommonItemCard(InputParams inputParams) { }
	// RVA: 0x21887d4 VA: 0x75947a07d4
	private Void _RenderRepItemCard(InputParams inputParams) { }
	// RVA: 0x2188f60 VA: 0x75947a0f60
	private UIItemCard _EnsureCommonItemCard(Single scale) { }
	// RVA: 0x21899ec VA: 0x75947a19ec
	private UIItemCard _EnsureRepItemCard(Single scale) { }
	// RVA: 0x2188e7c VA: 0x75947a0e7c
	private Void _ShowCard(UIItemCard card, Boolean show) { }
	// RVA: 0x2189cd4 VA: 0x75947a1cd4
	private Void _OnItemCardClicked(Int32 unusedIndex) { }
	// RVA: 0x2189e80 VA: 0x75947a1e80
	public Void .ctor() { }
}
```