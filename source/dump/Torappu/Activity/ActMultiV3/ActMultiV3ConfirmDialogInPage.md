# ActMultiV3ConfirmDialogInPage

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3ConfirmDialogView _viewPrefab`

- `Boolean m_isInited`

- `ActMultiV3ConfirmDialogView m_view`

- `ActMultiV3ConfirmDialogConfig m_config`


## Methods

- `Void _InitIfNot()`

- `Void _OnConfirm()`

- `Void _OnCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ConfirmDialogInPage : UICompDialog`1
{
	private ActMultiV3ConfirmDialogView _viewPrefab; // 0x48
	private Boolean m_isInited; // 0x50
	private ActMultiV3ConfirmDialogView m_view; // 0x58
	private ActMultiV3ConfirmDialogConfig m_config; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__OnConfirm; // 0x10
	private static DelegateBridge __Hotfix0__OnCancel; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30e5304 VA: 0x75956fd304
	private Void _InitIfNot() { }
	// RVA: 0x30e5400 VA: 0x75956fd400
	protected override Void OnRender(Option options) { }
	// RVA: 0x30e5584 VA: 0x75956fd584
	private Void _OnConfirm() { }
	// RVA: 0x30e5658 VA: 0x75956fd658
	private Void _OnCancel() { }
	// RVA: 0x30e572c VA: 0x75956fd72c
	public Void .ctor() { }
}
```