# CommonResourceBarBinder

**Namespace:** `Torappu.UI`


## Fields

- `PrefabInstHolder _resourceBarHolder`

- `CommonResourceBar m_resourceBar`

- `ResourceBarViewModel m_viewModelCache`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnResourceBarCreated(GameObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CommonResourceBarBinder : DataBinder`1
{
	private PrefabInstHolder _resourceBarHolder; // 0x20
	private CommonResourceBar m_resourceBar; // 0x28
	private ResourceBarViewModel m_viewModelCache; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__OnResourceBarCreated; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x22184b4 VA: 0x75948304b4
	private Void _InitIfNot() { }
	// RVA: 0x2218670 VA: 0x7594830670
	private Void _OnResourceBarCreated(GameObject inst) { }
	// RVA: 0x2218794 VA: 0x7594830794
	public override Void OnValueChanged(ResourceBarViewProperty property) { }
	// RVA: 0x2218890 VA: 0x7594830890
	public Void .ctor() { }
}
```