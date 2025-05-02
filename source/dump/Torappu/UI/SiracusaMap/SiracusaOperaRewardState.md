# SiracusaOperaRewardState

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaOperaRewardView _view`

- `RectTransform _backRt`

- `SiracusaOperaRewardStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnClose()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaRewardState : PopupFloatState
{
	private SiracusaOperaRewardView _view; // 0x70
	private RectTransform _backRt; // 0x78
	private SiracusaOperaRewardStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClose; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x23f8fb8 VA: 0x7594a10fb8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23f9020 VA: 0x7594a11020
	protected override Void OnEnter() { }
	// RVA: 0x23f9104 VA: 0x7594a11104
	private Void _InitIfNot() { }
	// RVA: 0x23f935c VA: 0x7594a1135c
	public Void EventOnClose() { }
	// RVA: 0x23f93d0 VA: 0x7594a113d0
	public Void .ctor() { }
	// RVA: 0x23f947c VA: 0x7594a1147c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```