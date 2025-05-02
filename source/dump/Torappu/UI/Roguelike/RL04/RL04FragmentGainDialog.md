# RL04FragmentGainDialog

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04FragmentGainView _view`

- `RL04FragmentGainProperty m_property`

- `Boolean m_hasInited`

- `Action m_onConfirm`


## Methods

- `Void _InitIfNot()`

- `Void _EventOnNextBtnClick()`

- `Void _EventOnCloseBtnClick()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentGainDialog : UICompDialog`1, IHotfixable
{
	private RL04FragmentGainView _view; // 0x48
	private RL04FragmentGainProperty m_property; // 0x50
	private Boolean m_hasInited; // 0x58
	private Action m_onConfirm; // 0x60
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__EventOnNextBtnClick; // 0x18
	private static DelegateBridge __Hotfix0__EventOnCloseBtnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2b22b48 VA: 0x759513ab48
	protected override Void OnInit() { }
	// RVA: 0x2b22d28 VA: 0x759513ad28
	protected override Void OnRender(Options input) { }
	// RVA: 0x2b22bbc VA: 0x759513abbc
	private Void _InitIfNot() { }
	// RVA: 0x2b23044 VA: 0x759513b044
	private Void _EventOnNextBtnClick() { }
	// RVA: 0x2b23168 VA: 0x759513b168
	private Void _EventOnCloseBtnClick() { }
	// RVA: 0x2b23254 VA: 0x759513b254
	public Void .ctor() { }
	// RVA: 0x2b2338c VA: 0x759513b38c
	private Void <>xLuaBaseProxy_OnInit() { }
}
```