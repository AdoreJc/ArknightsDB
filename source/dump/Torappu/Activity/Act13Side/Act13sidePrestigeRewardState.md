# Act13sidePrestigeRewardState

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Text _textOrgName`

- `SimpleLayoutContent _rankList`

- `RectTransform _backBtnRt`

- `Boolean m_hasInited`

- `Act13sidePrestigeRewardStateBean m_stateBean`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sidePrestigeRewardState : PopupFadeState
{
	private Text _textOrgName; // 0x70
	private SimpleLayoutContent _rankList; // 0x78
	private RectTransform _backBtnRt; // 0x80
	private Boolean m_hasInited; // 0x88
	private Act13sidePrestigeRewardStateBean m_stateBean; // 0x90
	private Adapter m_adapter; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3434798 VA: 0x7595a4c798
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3434800 VA: 0x7595a4c800
	protected override Void OnEnter() { }
	// RVA: 0x34348d4 VA: 0x7595a4c8d4
	private Void _InitIfNot() { }
	// RVA: 0x3434ab0 VA: 0x7595a4cab0
	public Void .ctor() { }
	// RVA: 0x3434b5c VA: 0x7595a4cb5c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```