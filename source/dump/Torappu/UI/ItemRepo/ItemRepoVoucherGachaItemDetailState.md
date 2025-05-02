# ItemRepoVoucherGachaItemDetailState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoVoucherGachaItemDetailStateBean m_stateBean`

- `SimpleLayoutContent _content`

- `Image _backImage`

- `CancelDragIfFits _cancelDragIfFits`

- `ItemRepoItemListAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnEnable()`

- `Void <OnEnable>b__9_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoVoucherGachaItemDetailState : PopupFloatState
{
	private ItemRepoVoucherGachaItemDetailStateBean m_stateBean; // 0x70
	private SimpleLayoutContent _content; // 0x78
	private Image _backImage; // 0x80
	private CancelDragIfFits _cancelDragIfFits; // 0x88
	private ItemRepoItemListAdapter m_adapter; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnEnable; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2d250c8 VA: 0x759533d0c8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d25130 VA: 0x759533d130
	private Void _InitIfNot() { }
	// RVA: 0x2d252d0 VA: 0x759533d2d0
	protected override Void OnEnter() { }
	// RVA: 0x2d25430 VA: 0x759533d430
	private Void OnEnable() { }
	// RVA: 0x2d25500 VA: 0x759533d500
	public Void .ctor() { }
	// RVA: 0x2d255ac VA: 0x759533d5ac
	private Void <OnEnable>b__9_0() { }
	// RVA: 0x2d25630 VA: 0x759533d630
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```