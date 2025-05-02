# FireworkCraftZoneBtnItem

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `GameObject _panelLocked`

- `GameObject _panelUnselected`

- `GameObject _panelSelected`

- `UIStateFinder m_stateFinder`

- `String m_cachedZoneId`


## Methods

- `Void Render(CraftZoneInfoModel, String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftZoneBtnItem : MonoBehaviour, IHotfixable
{
	private GameObject _panelLocked; // 0x18
	private GameObject _panelUnselected; // 0x20
	private GameObject _panelSelected; // 0x28
	private UIStateFinder m_stateFinder; // 0x30
	private String m_cachedZoneId; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29096f0 VA: 0x7594f216f0
	public Void Render(CraftZoneInfoModel model, String selectedZoneId) { }
	// RVA: 0x2909f44 VA: 0x7594f21f44
	public Void OnClick() { }
	// RVA: 0x290a034 VA: 0x7594f22034
	public Void .ctor() { }
}
```