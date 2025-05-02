# Act20sideCollectionState

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `RectTransform _topMenuContainer`

- `Act20sideCollectionView _view`

- `Boolean m_hasInited`

- `Act20sideCollectionStateBean m_stateBean`


## Methods

- `Void _OnCompItemClicked(String)`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCollectionState : PopupFadeState
{
	private RectTransform _topMenuContainer; // 0x70
	private Act20sideCollectionView _view; // 0x78
	private Boolean m_hasInited; // 0x80
	private Act20sideCollectionStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0__OnCompItemClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x32f6608 VA: 0x759590e608
	protected override Void OnEnter() { }
	// RVA: 0x32f6858 VA: 0x759590e858
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32f68c0 VA: 0x759590e8c0
	private Void _OnCompItemClicked(String compId) { }
	// RVA: 0x32f66b8 VA: 0x759590e6b8
	private Void _InitIfNot() { }
	// RVA: 0x32f6b68 VA: 0x759590eb68
	public Void .ctor() { }
	// RVA: 0x32f6cc0 VA: 0x759590ecc0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```