# Act36sideZoneMapContainerArrowView

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `GameObject _iconActive`

- `GameObject _iconInactive`

- `GameObject _hotspot`

- `Action onArrowClick`


## Methods

- `Void Render(Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideZoneMapContainerArrowView : MonoBehaviour, IHotfixable
{
	private GameObject _iconActive; // 0x18
	private GameObject _iconInactive; // 0x20
	private GameObject _hotspot; // 0x28
	public Action onArrowClick; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x324ff68 VA: 0x7595867f68
	public Void Render(Boolean active) { }
	// RVA: 0x3250014 VA: 0x7595868014
	public Void OnClick() { }
	// RVA: 0x3250098 VA: 0x7595868098
	public Void .ctor() { }
}
```