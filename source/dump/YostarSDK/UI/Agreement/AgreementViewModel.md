# AgreementViewModel

**Namespace:** `YostarSDK.UI.Agreement`


## Fields

- `Boolean needToAgree`

- `Boolean isConfirmed`

- `Boolean useSeparateConfirm`


## Methods

- `Void LoadData(AgreementOptions)`

- `Boolean CheckIfShowToggle()`

- `Boolean CheckIfValidToAgree()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI.Agreement
public class AgreementViewModel : IHotfixable
{
	public Boolean needToAgree; // 0x10
	public Boolean isConfirmed; // 0x11
	public Boolean useSeparateConfirm; // 0x12
	public List`1 agreeItems; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfShowToggle; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfValidToAgree; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2580f5c VA: 0x7594b98f5c
	public Void LoadData(AgreementOptions options) { }
	// RVA: 0x258187c VA: 0x7594b9987c
	public Boolean CheckIfShowToggle() { }
	// RVA: 0x258096c VA: 0x7594b9896c
	public Boolean CheckIfValidToAgree() { }
	// RVA: 0x25819f8 VA: 0x7594b999f8
	public Void .ctor() { }
}
```