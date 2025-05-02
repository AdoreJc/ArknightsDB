# AgreementItemModel

**Namespace:** `YostarSDK.UI.Agreement`


## Fields

- `Int32 index`

- `Boolean isConfirmed`

- `Boolean useSeparateConfirm`

- `Boolean isShow`

- `String content`

- `Boolean needToAgree`


## Methods

- `String GetConfirmText()`

- `Boolean CheckIfShowToggle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI.Agreement
public class AgreementItemModel : IHotfixable
{
	public Int32 index; // 0x10
	public Boolean isConfirmed; // 0x14
	public Boolean useSeparateConfirm; // 0x15
	public Boolean isShow; // 0x16
	public String content; // 0x18
	public Boolean needToAgree; // 0x20
	private static DelegateBridge __Hotfix0_GetConfirmText; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfShowToggle; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2581dc4 VA: 0x7594b99dc4
	public String GetConfirmText() { }
	// RVA: 0x2581d44 VA: 0x7594b99d44
	public Boolean CheckIfShowToggle() { }
	// RVA: 0x258263c VA: 0x7594b9a63c
	public Void .ctor() { }
}
```