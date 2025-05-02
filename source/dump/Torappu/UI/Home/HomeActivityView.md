# HomeActivityView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _background`

- `ActivityViewEntry m_entry`


## Methods

- `Void EventOnBannerClick()`

- `Void Render(ActivityViewEntry)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeActivityView : MonoBehaviour, IHotfixable
{
	private Image _background; // 0x18
	private ActivityViewEntry m_entry; // 0x20
	private static DelegateBridge __Hotfix0_EventOnBannerClick; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2832fe8 VA: 0x7594e4afe8
	public Void EventOnBannerClick() { }
	// RVA: 0x2833068 VA: 0x7594e4b068
	public Void Render(ActivityViewEntry entry) { }
	// RVA: 0x2833158 VA: 0x7594e4b158
	private Void OnDestroy() { }
	// RVA: 0x28331c8 VA: 0x7594e4b1c8
	public Void .ctor() { }
}
```