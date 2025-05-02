# HomeSecretarySkinItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _headIcon`

- `GameObject _objNotSelected`

- `GameObject _objInPreview`

- `String m_skinId`

- `UIStateFinder m_stateFinder`


## Methods

- `Void ApplyData(HomeSecretarySkinItemModel, Boolean, Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretarySkinItemView : MonoBehaviour, IHotfixable
{
	private Image _headIcon; // 0x18
	private GameObject _objNotSelected; // 0x20
	private GameObject[] _objListSelected; // 0x28
	private GameObject _objInPreview; // 0x30
	private String m_skinId; // 0x38
	private UIStateFinder m_stateFinder; // 0x40
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x283ec20 VA: 0x7594e56c20
	public Void ApplyData(HomeSecretarySkinItemModel model, Boolean isSelected, Boolean isInPreview) { }
	// RVA: 0x283fa04 VA: 0x7594e57a04
	public Void OnClick() { }
	// RVA: 0x283faf4 VA: 0x7594e57af4
	public Void .ctor() { }
}
```