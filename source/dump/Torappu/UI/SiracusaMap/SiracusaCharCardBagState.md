# SiracusaCharCardBagState

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaCharCardBagView _view`

- `RectTransform _backRt`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnClose()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharCardBagState : PopupFloatState
{
	private SiracusaCharCardBagView _view; // 0x70
	private RectTransform _backRt; // 0x78
	private Boolean m_hasInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClose; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x23e4180 VA: 0x75949fc180
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23e41e4 VA: 0x75949fc1e4
	protected override Void OnEnter() { }
	// RVA: 0x23e4414 VA: 0x75949fc414
	private Void _InitIfNot() { }
	// RVA: 0x23e45a8 VA: 0x75949fc5a8
	public Void EventOnClose() { }
	// RVA: 0x23e461c VA: 0x75949fc61c
	public Void .ctor() { }
	// RVA: 0x23e468c VA: 0x75949fc68c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```