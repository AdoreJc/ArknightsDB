# HandBookV2ForceDetailStateBean

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2GroupCharViewModel m_charViewModel`

- `Vector3 pos`

- `Vector3 scale`


## Properties

- `HandBookV2GroupCharViewModel charViewModel`


## Methods

- `HandBookV2GroupCharViewModel get_charViewModel()`

- `Void SetCharViewModel(UIPage, HandBookV2GroupCharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2ForceDetailStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	private HandBookV2GroupCharViewModel m_charViewModel; // 0x18
	public Vector3 pos; // 0x20
	public Vector3 scale; // 0x2c
	private static DelegateBridge __Hotfix0_get_charViewModel; // 0x0
	private static DelegateBridge __Hotfix0_SetCharViewModel; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public HandBookV2GroupCharViewModel charViewModel { get; }

	// RVA: 0x2edc238 VA: 0x75954f4238
	public HandBookV2GroupCharViewModel get_charViewModel() { }
	// RVA: 0x2edc2a0 VA: 0x75954f42a0
	public Void SetCharViewModel(UIPage page, HandBookV2GroupCharViewModel value) { }
	// RVA: 0x2edc3fc VA: 0x75954f43fc
	public Void .ctor() { }
}
```