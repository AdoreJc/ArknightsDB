# ActMultiV3ManualTitleSelectState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3ManualTitleSelectView _view`

- `RectTransform _backRect`

- `String m_actId`

- `Boolean m_inited`

- `ActMultiV3TitleSelectProperty m_prop`

- `String m_cachedPrefixId`

- `String m_cachedSuffixId`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnBeginDrag()`

- `Void _OnEndDrag(TitlePagerSelection)`

- `Void _OnClickItem(TitlePagerSelection)`

- `Void _OnConfirmTitle()`

- `Void _InitIfNot()`

- `String _GetActivityId()`

- `Boolean _IsStateStable()`

- `Void <_OnConfirmTitle>b__18_0(ActMultiV3ChangeTitleResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualTitleSelectState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 ON_BEGIN_DRAG; // 0x0
	public const Int32 ON_END_DRAG; // 0x0
	public const Int32 ON_ITEM_CLICK; // 0x0
	public const Int32 ON_CONFIRM_TITLE; // 0x0
	private ActMultiV3ManualTitleSelectView _view; // 0x70
	private RectTransform _backRect; // 0x78
	private String m_actId; // 0x80
	private Boolean m_inited; // 0x88
	private ActMultiV3TitleSelectProperty m_prop; // 0x90
	private String m_cachedPrefixId; // 0x98
	private String m_cachedSuffixId; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0__OnBeginDrag; // 0x18
	private static DelegateBridge __Hotfix0__OnEndDrag; // 0x20
	private static DelegateBridge __Hotfix0__OnClickItem; // 0x28
	private static DelegateBridge __Hotfix0__OnConfirmTitle; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__GetActivityId; // 0x40
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x30fb2d8 VA: 0x75957132d8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30fb33c VA: 0x759571333c
	protected override Void OnEnter() { }
	// RVA: 0x30fb594 VA: 0x7595713594
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x30fb724 VA: 0x7595713724
	private Void _OnBeginDrag() { }
	// RVA: 0x30fb7e0 VA: 0x75957137e0
	private Void _OnEndDrag(TitlePagerSelection selection) { }
	// RVA: 0x30fb8cc VA: 0x75957138cc
	private Void _OnClickItem(TitlePagerSelection selection) { }
	// RVA: 0x30fb9bc VA: 0x75957139bc
	private Void _OnConfirmTitle() { }
	// RVA: 0x30fb450 VA: 0x7595713450
	private Void _InitIfNot() { }
	// RVA: 0x30fbfb0 VA: 0x7595713fb0
	private String _GetActivityId() { }
	// RVA: 0x30fbea8 VA: 0x7595713ea8
	private Boolean _IsStateStable() { }
	// RVA: 0x30fc0ac VA: 0x75957140ac
	public Void .ctor() { }
	// RVA: 0x30fc15c VA: 0x759571415c
	private Void <_OnConfirmTitle>b__18_0(ActMultiV3ChangeTitleResponse response) { }
	// RVA: 0x30fc16c VA: 0x759571416c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```