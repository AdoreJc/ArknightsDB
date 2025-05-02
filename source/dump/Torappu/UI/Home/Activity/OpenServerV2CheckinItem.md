# OpenServerV2CheckinItem

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `Text _txtIndex`

- `Text _txtName`

- `CanvasGroup _neverGet`

- `RectTransform _transformCheckinValid`

- `RectTransform _alreadyGet`

- `RectTransform _alreadyGet2`

- `Image _upPart`

- `Image _downPart`

- `GameObject _canGet`

- `GameObject _canGetHotspot`

- `GameObject _objItem`

- `GameObject _itemDescHotspot`

- `UIAnimationLocation _animationLocation`

- `Int32 m_index`

- `UIItemViewModel m_itemViewModel`

- `Tween m_tween`


## Methods

- `Void Render(RenderParam)`

- `Void OnClick()`

- `Void OnItemDescShowClick()`

- `Void _OnItemClick()`

- `Void <OnClick>b__23_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2CheckinItem : MonoBehaviour, IHotfixable
{
	private Text _txtIndex; // 0x18
	private Text _txtName; // 0x20
	private Image[] _imgIcons; // 0x28
	private Text[] _txtCounts; // 0x30
	private CanvasGroup _neverGet; // 0x38
	private RectTransform _transformCheckinValid; // 0x40
	private RectTransform _alreadyGet; // 0x48
	private RectTransform _alreadyGet2; // 0x50
	private Image _upPart; // 0x58
	private Image _downPart; // 0x60
	private List`1 _upSpritePart; // 0x68
	private List`1 _downSpritePart; // 0x70
	private GameObject _canGet; // 0x78
	private GameObject _canGetHotspot; // 0x80
	private GameObject _objItem; // 0x88
	private GameObject _itemDescHotspot; // 0x90
	private UIAnimationLocation _animationLocation; // 0x98
	private Int32 m_index; // 0xa8
	private Action`1 m_clickAction; // 0xb0
	private UIItemViewModel m_itemViewModel; // 0xb8
	private Tween m_tween; // 0xc0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_OnItemDescShowClick; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28542e0 VA: 0x7594e6c2e0
	public Void Render(RenderParam renderParam) { }
	// RVA: 0x2855010 VA: 0x7594e6d010
	public Void OnClick() { }
	// RVA: 0x2855210 VA: 0x7594e6d210
	public Void OnItemDescShowClick() { }
	// RVA: 0x2855188 VA: 0x7594e6d188
	private Void _OnItemClick() { }
	// RVA: 0x28552dc VA: 0x7594e6d2dc
	public Void .ctor() { }
	// RVA: 0x285534c VA: 0x7594e6d34c
	private Void <OnClick>b__23_0() { }
}
```