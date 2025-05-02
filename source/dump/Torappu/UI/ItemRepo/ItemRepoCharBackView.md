# ItemRepoCharBackView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `UIAtlasImage _charProtrait`

- `GameObject _hotspot`

- `UIStringEvent onClickEvent`

- `String m_cacheCharId`


## Methods

- `Void OnClick()`

- `Void Render(ItemBundle, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoCharBackView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _charProtrait; // 0x18
	private GameObject _hotspot; // 0x20
	public UIStringEvent onClickEvent; // 0x28
	private String m_cacheCharId; // 0x30
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d312e8 VA: 0x75953492e8
	public Void OnClick() { }
	// RVA: 0x2d3137c VA: 0x759534937c
	public Void Render(ItemBundle charInfo, Boolean clickable) { }
	// RVA: 0x2d31518 VA: 0x7595349518
	public Void .ctor() { }
}
```