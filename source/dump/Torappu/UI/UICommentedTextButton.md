# UICommentedTextButton

**Namespace:** `Torappu.UI`


## Fields

- `Image _bkgLight`

- `Image _bkgDark`

- `Image _imgLine`

- `Color _darkColor`

- `Color _lightColor`

- `RectTransform _hotzone`

- `Boolean UseDarkColor`

- `UITermDescDataModel m_paramPair`

- `RectTransform m_rectTrans`


## Methods

- `Void Init(UICommentedTextData)`

- `Void SetSize(Vector2, Vector2, Vector3)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICommentedTextButton : MonoBehaviour, IHotfixable
{
	private Image _bkgLight; // 0x18
	private Image _bkgDark; // 0x20
	private Image _imgLine; // 0x28
	private Color _darkColor; // 0x30
	private Color _lightColor; // 0x40
	private RectTransform _hotzone; // 0x50
	public Action`1 OnClickEvent; // 0x58
	public Boolean UseDarkColor; // 0x60
	private UITermDescDataModel m_paramPair; // 0x68
	private RectTransform m_rectTrans; // 0x78
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_SetSize; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2245788 VA: 0x759485d788
	public Void Init(UICommentedTextData data) { }
	// RVA: 0x2245a48 VA: 0x759485da48
	public Void SetSize(Vector2 sizeDelta, Vector2 hotzone, Vector3 anchor3D) { }
	// RVA: 0x2245e80 VA: 0x759485de80
	public Void EventOnClick() { }
	// RVA: 0x2245f14 VA: 0x759485df14
	public Void .ctor() { }
}
```