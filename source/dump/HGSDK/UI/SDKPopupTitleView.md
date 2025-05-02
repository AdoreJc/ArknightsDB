# SDKPopupTitleView

**Namespace:** `HGSDK.UI`


## Fields

- `GameObject _btnBack`

- `GameObject _btnClose`

- `Options m_options`


## Methods

- `Void SetOptions(Options)`

- `Void EventOnCloseClicked()`

- `Void EventOnBackClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKPopupTitleView : MonoBehaviour, IHotfixable
{
	private GameObject _btnBack; // 0x18
	private GameObject _btnClose; // 0x20
	private Options m_options; // 0x28
	private static DelegateBridge __Hotfix0_SetOptions; // 0x0
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3752438 VA: 0x7595d6a438
	public Void SetOptions(Options options) { }
	// RVA: 0x3752560 VA: 0x7595d6a560
	public Void EventOnCloseClicked() { }
	// RVA: 0x37525e4 VA: 0x7595d6a5e4
	public Void EventOnBackClicked() { }
	// RVA: 0x3752668 VA: 0x7595d6a668
	public Void .ctor() { }
}
```