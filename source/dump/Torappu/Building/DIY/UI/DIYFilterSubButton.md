# DIYFilterSubButton

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Text _text`

- `GameObject _pnlTrackpoint`

- `FurnitureSubType m_subType`

- `String m_textContent`


## Properties

- `FurnitureSubType subType`

- `String textContent`


## Methods

- `FurnitureSubType get_subType()`

- `Void set_subType(FurnitureSubType)`

- `String get_textContent()`

- `Void set_textContent(String)`

- `Void OnButtonPressed()`

- `Void SetTextColor(Color)`

- `Void SetWidth(Single)`

- `Void RenderTrackPointStatus(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFilterSubButton : MonoBehaviour, IHotfixable
{
	private Text _text; // 0x18
	private GameObject _pnlTrackpoint; // 0x20
	public Action`1 onSubTypePressed; // 0x28
	private FurnitureSubType m_subType; // 0x30
	private String m_textContent; // 0x38
	private static DelegateBridge __Hotfix0_get_subType; // 0x0
	private static DelegateBridge __Hotfix0_set_subType; // 0x8
	private static DelegateBridge __Hotfix0_get_textContent; // 0x10
	private static DelegateBridge __Hotfix0_set_textContent; // 0x18
	private static DelegateBridge __Hotfix0_OnButtonPressed; // 0x20
	private static DelegateBridge __Hotfix0_SetTextColor; // 0x28
	private static DelegateBridge __Hotfix0_SetWidth; // 0x30
	private static DelegateBridge __Hotfix0_RenderTrackPointStatus; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public FurnitureSubType subType { get; set; }
	public String textContent { get; set; }

	// RVA: 0x3816098 VA: 0x7595e2e098
	public FurnitureSubType get_subType() { }
	// RVA: 0x3816100 VA: 0x7595e2e100
	public Void set_subType(FurnitureSubType value) { }
	// RVA: 0x381617c VA: 0x7595e2e17c
	public String get_textContent() { }
	// RVA: 0x38161e4 VA: 0x7595e2e1e4
	public Void set_textContent(String value) { }
	// RVA: 0x3816288 VA: 0x7595e2e288
	public Void OnButtonPressed() { }
	// RVA: 0x3816310 VA: 0x7595e2e310
	public Void SetTextColor(Color color) { }
	// RVA: 0x38163d4 VA: 0x7595e2e3d4
	public Void SetWidth(Single width) { }
	// RVA: 0x3816478 VA: 0x7595e2e478
	public Void RenderTrackPointStatus(Boolean hasTrackpoint) { }
	// RVA: 0x38164fc VA: 0x7595e2e4fc
	public Void .ctor() { }
}
```