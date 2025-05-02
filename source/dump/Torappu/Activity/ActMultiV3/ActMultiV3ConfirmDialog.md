# ActMultiV3ConfirmDialog

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
public class ActMultiV3ConfirmDialog : UICustomDialog`1
{
	private ActMultiV3ConfirmDialogView _viewPrefab; // 0x40
	private Boolean m_isInited; // 0x48
	private ActMultiV3ConfirmDialogView m_view; // 0x50
	private ActMultiV3ConfirmDialogConfig m_config; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__OnConfirm; // 0x10
	private static DelegateBridge __Hotfix0__OnCancel; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30e4c88 VA: 0x75956fcc88
	private Void _InitIfNot() { }
	// RVA: 0x30e4d84 VA: 0x75956fcd84
	protected override Void OnRender(Option options) { }
	// RVA: 0x30e516c VA: 0x75956fd16c
	private Void _OnConfirm() { }
	// RVA: 0x30e51f0 VA: 0x75956fd1f0
	private Void _OnCancel() { }
	// RVA: 0x30e5274 VA: 0x75956fd274
	public Void .ctor() { }
}
```